# **FS Module**

### **Fs read file Asynchronous**

```jsx
const fs = require('fs');
const http = require('http');

const server = http.createServer((req, res) => {
    if (req.url === "/") {
        // Asynchronous file read with correct path
        fs.readFile(`${__dirname}/Home.html`, function (error, data) {
            if (error) {
                // Handle the error (e.g., file not found)
                res.writeHead(500, { 'Content-Type': 'text/plain' });
                res.write("Internal Server Error: Could not read file.");
                res.end();
                console.error("Error reading file:", error); // Log the actual error for debugging
            } else {
                // No error, send the file content
                res.writeHead(200, { 'Content-Type': 'text/html' });
                res.write(data);
                res.end();
            }
        });
    }
});

server.listen(4040);
console.log("Server Run Success");

```

এই কোডটি একটি নোড.js (Node.js) সার্ভার তৈরি করে যা একটি HTTP রিকুয়েস্টের জবাবে একটি HTML ফাইল পাঠায়। কোডটি ধাপে ধাপে ব্যাখ্যা করা হলো:

### কোড ব্যাখ্যা (বাংলায়):

### 1. **মডিউল ইম্পোর্ট (Modules Import):**

```jsx
const fs = require('fs');
const http = require('http');

```

- `fs`: এটি Node.js এর ফাইল সিস্টেম মডিউল, যা ফাইল পড়া এবং লেখা করতে ব্যবহার করা হয়।
- `http`: এটি Node.js এর HTTP মডিউল, যা সার্ভার তৈরি করতে ব্যবহৃত হয়।

### 2. **সার্ভার তৈরি করা (Creating the Server):**

```jsx
const server = http.createServer((req, res) => {
```

- `http.createServer`: এটি একটি সার্ভার তৈরি করে। সার্ভারটি প্রতিটি রিকুয়েস্ট পাওয়ার সাথে সাথে একটি ফাংশন চালায়, যেখানে `req` (রিকুয়েস্ট) এবং `res` (রেসপন্স) প্যারামিটার হিসেবে ব্যবহৃত হয়।
- `req`: ক্লায়েন্ট থেকে আসা HTTP রিকুয়েস্টের তথ্য ধারণ করে।
- `res`: সার্ভারের রেসপন্স বা জবাবকে হ্যান্ডেল করে, যা সার্ভার ক্লায়েন্টকে পাঠায়।

### 3. **রিকুয়েস্ট URL চেক করা (Checking the Request URL):**

```jsx
if (req.url === "/") {
```

- এই অংশে চেক করা হচ্ছে যে ক্লায়েন্টের রিকুয়েস্টের URLটি `/` কিনা। অর্থাৎ, হোম পেজ রিকুয়েস্ট করা হয়েছে কিনা।

### 4. **ফাইল পড়া (Reading the File):**

```jsx
fs.readFile(`${__dirname}/Home.html`, function (error, data) {
```

- `fs.readFile`: এটি একটি অ্যাসিনক্রোনাস (Asynchronous) মেথড যা একটি ফাইল পড়ে। এখানে `${__dirname}/Home.html` দিয়ে ফাইলের সম্পূর্ণ পাথ (path) দেয়া হয়েছে, যেখানে `__dirname` বর্তমান স্ক্রিপ্টের ডিরেক্টরির পাথ নির্দেশ করে।
- `function (error, data)`: ফাইলটি পড়া সম্পন্ন হলে এই ফাংশনটি কল হয়। ফাইলটি পড়তে কোনো সমস্যা হলে `error` প্যারামিটারটি সেট হয়, আর ফাইলের ডেটা সফলভাবে পড়া গেলে সেটি `data` প্যারামিটারে রাখা হয়।

### 5. **এরর হ্যান্ডলিং (Handling Errors):**

```jsx
if (error) {
    res.writeHead(500, { 'Content-Type': 'text/plain' });
    res.write("Internal Server Error: Could not read file.");
    res.end();
    console.error("Error reading file:", error);
}

```

- যদি কোনো এরর ঘটে (যেমন ফাইলটি পাওয়া যায় না), তাহলে সার্ভার ৫০০ স্ট্যাটাস কোড (Internal Server Error) সহ একটি রেসপন্স পাঠায়।
- `res.writeHead(500)`: এখানে ৫০০ মানে সার্ভারের ইন্টারনাল কোনো সমস্যা হয়েছে।
- `console.error`: এটি সার্ভারের কনসোলে নির্দিষ্ট এরর মেসেজ প্রিন্ট করে, যা ডেভেলপারের জন্য ডিবাগিংয়ের সময় সহায়ক।

### 6. **ফাইল সফলভাবে রেসপন্স পাঠানো (Sending File as Response):**

```jsx
else {
    res.writeHead(200, { 'Content-Type': 'text/html' });
    res.write(data);
    res.end();
}
```

- যদি কোনো এরর না ঘটে, তাহলে সার্ভার `200 OK` স্ট্যাটাস কোড সহ HTML ফাইলটি পাঠিয়ে দেয়।
- `res.writeHead(200)`: ২০০ মানে রিকুয়েস্ট সফল হয়েছে।
- `res.write(data)`: এই অংশে `Home.html` ফাইলের কনটেন্ট ক্লায়েন্টের কাছে পাঠানো হয়।
- `res.end()`: এটি রেসপন্স শেষ করে দেয়, অর্থাৎ সার্ভার জানায় যে রেসপন্স পাঠানো সম্পন্ন হয়েছে।

### 7. **সার্ভার লিসেনিং শুরু করা (Server Listening):**

```jsx
server.listen(4040);
console.log("Server Run Success");
```

- `server.listen(4040)`: সার্ভারটি পোর্ট ৪০৪০-এ ক্লায়েন্টের রিকুয়েস্ট শোনার জন্য অপেক্ষা করবে।
- `console.log("Server Run Success")`: সার্ভার সফলভাবে চালু হলে এটি কনসোলে "Server Run Success" প্রিন্ট করবে।

### সংক্ষেপে:

এই কোডটি Node.js এর একটি সার্ভার তৈরি করে, যেখানে `/` URL এ অ্যাক্সেস করলে `Home.html` ফাইলটি পাঠানো হয়। যদি ফাইলটি পড়তে কোনো সমস্যা হয়, তাহলে সার্ভার একটি এরর মেসেজ পাঠায়।

## **fs read file Synchronous**

```jsx
const fs = require('fs');
const http = require('http');

const server = http.createServer((req, res) => {
    if (req.url === "/") { // Use '===' for comparison
        try {
            let myData = fs.readFileSync(`${__dirname}/Home.html`);
            res.writeHead(200, { 'Content-Type': 'text/html' });
            res.write(myData);
            res.end();
        } catch (err) {
            console.error("Error reading file:", err);
            res.writeHead(500);
            res.end("Internal Server Error");
        }
    }
});


server.listen(5050);
console.log("Server Run Success");

```

এই কোডটি Node.js দিয়ে একটি সার্ভার তৈরি করে, যা একটি HTTP রিকুয়েস্ট আসার পর সাড়া দেয়। সার্ভারটি `/` (হোম পেজ) URL-এ রিকুয়েস্ট করা হলে একটি HTML ফাইল পাঠায়। কোডটি ধাপে ধাপে বিশ্লেষণ করা হলো:

### কোড ব্যাখ্যা (বাংলায়):

### 1. **মডিউল ইম্পোর্ট (Modules Import):**

```jsx
const fs = require('fs');
const http = require('http');
```

- `fs`: এটি Node.js এর ফাইল সিস্টেম মডিউল, যা ফাইল পড়া এবং লেখা করতে ব্যবহৃত হয়। এখানে এটি `readFileSync` মেথড ব্যবহার করে সিঙ্ক্রোনাস (Synchronous) ফাইল পড়ার জন্য ব্যবহৃত হচ্ছে।
- `http`: এটি Node.js এর HTTP মডিউল, যা সার্ভার তৈরি করতে ব্যবহৃত হয়।

### 2. **সার্ভার তৈরি করা (Creating the Server):**

```jsx
const server = http.createServer((req, res) => {
```

- `http.createServer`: এটি একটি সার্ভার তৈরি করে, যা HTTP রিকুয়েস্ট পাওয়ার সময় কলব্যাক ফাংশন চালায়। এই ফাংশন দুটি প্যারামিটার নেয়:
    - `req`: রিকুয়েস্ট অবজেক্ট, যা ক্লায়েন্টের রিকুয়েস্ট সম্পর্কিত তথ্য ধারণ করে।
    - `res`: রেসপন্স অবজেক্ট, যা সার্ভারের জবাব বা রেসপন্স ধারণ করে এবং তা ক্লায়েন্টকে পাঠায়।

### 3. **রিকুয়েস্ট URL চেক করা (Checking the Request URL):**

```jsx
if (req.url === "/") {
```

- এখানে চেক করা হচ্ছে যে রিকুয়েস্টের URL `/` কিনা। অর্থাৎ, ক্লায়েন্ট যদি সার্ভারের হোম পেজ রিকুয়েস্ট করে, তাহলে এই কোডটি এক্সিকিউট হবে।

### 4. **সিঙ্ক্রোনাস ফাইল পড়া (Synchronous File Reading):**

```jsx
try {
    let myData = fs.readFileSync(`${__dirname}/Home.html`);
```

- `fs.readFileSync`: এটি একটি সিঙ্ক্রোনাস মেথড, যা ফাইল পড়ে এবং অবিলম্বে ফাইলের কন্টেন্ট রিটার্ন করে। এখানে `${__dirname}` ব্যবহার করে ফাইলের সম্পূর্ণ পাথ (path) নির্দেশ করা হয়েছে।
    - `__dirname`: এটি স্ক্রিপ্টের বর্তমান ডিরেক্টরির পাথ প্রদান করে, যাতে ফাইলের অবস্থান সঠিকভাবে নির্ধারণ করা যায়।
    - `Home.html`: এই ফাইলটি সার্ভার থেকে পাঠানো হবে।

### 5. **সফলভাবে রেসপন্স পাঠানো (Sending Successful Response):**

```jsx
res.writeHead(200, { 'Content-Type': 'text/html' });
res.write(myData);
res.end();
```

- `res.writeHead(200)`: এটি HTTP রেসপন্সের হেডার পাঠায়, যেখানে `200` মানে রিকুয়েস্ট সফল হয়েছে।
    - `'Content-Type': 'text/html'`: এখানে Content-Type নির্ধারণ করা হয়েছে যে সার্ভার HTML ডেটা পাঠাচ্ছে।
- `res.write(myData)`: সার্ভার ফাইলের কনটেন্ট ক্লায়েন্টের কাছে পাঠাচ্ছে।
- `res.end()`: রেসপন্স সম্পন্ন করার জন্য `res.end()` মেথড ব্যবহার করা হয়েছে, যা সার্ভারকে জানায় যে রেসপন্স পাঠানো শেষ হয়েছে।

### 6. **এরর হ্যান্ডলিং (Handling Errors):**

```jsx
} catch (err) {
    console.error("Error reading file:", err);
    res.writeHead(500);
    res.end("Internal Server Error");
}
```

- `try-catch`: এটি এরর হ্যান্ডল করার জন্য ব্যবহৃত হয়। যদি `fs.readFileSync` কোনো এরর ফেলে (যেমন ফাইলটি না পাওয়া যায়), তাহলে `catch` ব্লকে গিয়ে এরর হ্যান্ডল করা হয়।
    - `res.writeHead(500)`: ৫০০ মানে ইন্টারনাল সার্ভার এরর (Internal Server Error)। এটি দেখায় যে সার্ভার ফাইল পড়তে ব্যর্থ হয়েছে।
    - `console.error`: এটি কনসোলে প্রকৃত এরর মেসেজ প্রিন্ট করে, যা ডেভেলপারের জন্য ডিবাগ করতে সহায়ক।

### 7. **সার্ভার লিসেন করা (Server Listening):**

```jsx
server.listen(5050);
console.log("Server Run Success");
```

- `server.listen(5050)`: সার্ভারটি পোর্ট ৫০৫০-এ চালু হয়েছে এবং যেকোনো ইনকামিং রিকুয়েস্ট শোনার জন্য প্রস্তুত।
- `console.log("Server Run Success")`: এটি কনসোলে মেসেজ প্রিন্ট করে দেখায় যে সার্ভার সফলভাবে চালু হয়েছে।

### সংক্ষেপে:

এই কোডটি Node.js এর মাধ্যমে একটি HTTP সার্ভার তৈরি করে, যা `/` URL থেকে রিকুয়েস্ট আসলে `Home.html` ফাইলটি পাঠায়। যদি ফাইলটি পড়া না যায়, তাহলে ৫০০ ইন্টারনাল সার্ভার এরর পাঠানো হয়।