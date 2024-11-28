# Node.JS-Learning-Journey
# **NodeJS**

```jsx
npm i lodash
```

**NodeJs Pachage**

```jsx
npm init --y
```

```jsx
npm i
```

**npm install nodemon**

```jsx
npm i nodemon
```

**npm install yarn**

```jsx
yarn add react
```

# 1.What is NodeJS

1. **JavaScript Runtime:** Node.js is an open-source, cross-platform runtime environment for executing JavaScript code outside of a browser.
2. **NodeJS** is a JavaScript in a different environment means Running JS on the server or any computer.
3. **Built on Chrome's V8 Engine:** It runs on the V8 engine, which compiles JavaScript directly to native machine code, enhancing performance.
4. **V8** is written in C++ for speed.
5. V8 + Backend Features = NodeJS

# **2.What is NodeJS**

1. **Design:**  Features an event-driven, non-blocking I/O model for efficiency.
2. **Full-Stack JavaScript:** Allows using JavaScript on both server and client
sides.
3. **Scalability:** Ideal for scalable network applications due to its architecture.
4. **Versatility:** Suitable for web, real-time chat, and REST API servers.

# 3. NodeJS Features(Added)

![Screenshot 2024-10-17 234134.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/e1399429-47d4-4d0e-9b46-ae790c4857ab/Screenshot_2024-10-17_234134.png)

1. **Non-blocking I/O:** Designed to perform non-blocking operations by default, making it suitable for I/O-heavy operations.
2. **Networking Support:** Supports TCP/UDP sockets, which are crucial for building lower-level network applications that browsers can’t handle.

# NodeJS Features

![Screenshot 2024-10-17 234925.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/5a51e01a-67c5-4074-b241-7a799592f8b5/Screenshot_2024-10-17_234925.png)

1. **File System Access: Provides APIs to read and write files directly, which is not possible in browser environments for security
reasons.**
2. **Server-Side Capabilities: Node.js enables JavaScript to run on the server, handling HTTP requests, file operations, and other server-side functionalities.**
3. **Modules: Organize code into reusable modules using require().**

# 4. JavaScript on Client

![Screenshot 2024-10-17 235412.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/203e37c0-7227-428e-9408-6638b0e195b2/Screenshot_2024-10-17_235412.png)

1. **Displays Web Page:** Turns HTML code into what you see on screen.
2. **User Clicks:** Helps you interact with the web page.
3. **Updates Content:** Allows changes to the page using JavaScript.
4. **Loads Files:** Gets HTML, images, etc., from the server.

# **5. JavaScript on Server**

1. **Database Management:** Stores, retrieves, and manages data efficiently through operations like CRUD (Create, Read, Update, Delete).
2. **Authentication:** Verifies user identities to control access to the system, ensuring that users are who they claim to be.
3. **Authorization:** Determines what authenticated users are allowed to do by managing permissions and access controls.
4. **Input Validation:** Checks incoming data for correctness, completeness, and security to prevent malicious data entry
and errors.
5. **Session Management:** Tracks user activity across various requests to maintain state and manage user-specific
settings
6. **API Management:** Provides and handles interfaces for applications to interact, ensuring smooth data exchange and integration.
7. **Error Handling:** Manages and responds to errors effectively to maintain system stability and provide useful error messages.
8.  **Security Measures:** Implements protocols to protect data from unauthorized access and attacks, such as SQL injection and
cross-site scripting (XSS).
9.  **Data Encryption:** Secures sensitive information by encrypting data stored in databases and during transmission.
10.  **Logging and Monitoring:** Keeps records of system activity to diagnose issues and monitor system health and security.

# **6. Client Code vs Server Code**

![Screenshot 2024-10-19 151814.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/2d3cfca8-6986-4f87-9f36-3e50dffb4f8f/Screenshot_2024-10-19_151814.png)

1. User/client can’t access server code directly.
2. Client must raise requests for particular APIs to access certain features or data.
3. **Environment Access:** Server-side JavaScript accesses server features like file systems and
databases.
4. **Security:** Server-side code can handle sensitive operations securely, while client-side code is
exposed and must manage security risks.
5. **Performance:** Heavy computations are better performed on the server to avoid slowing down
the client.
6. **Resource Utilization:** Servers generally offer more powerful processing capabilities than client
devices.
7. **Data Handling:** Server-side can directly manage large data sets and database interactions, unlike
client-side JavaScript.
8. **Asynchronous Operations:** Server-side JavaScript is optimized for non-blocking I/O to efficiently manage multiple requests.
9. **Session Management:** Servers handle sessions and user states more comprehensively.
10. **Scalability:** Server-side code is designed to scale and handle requests from multiple clients simultaneously.

# **7. Other uses of NodeJS**

1. **Local Utility Scripts:** Automates tasks and processes files locally, like using shell scripts
but with JavaScript.
2.  **Internet of Things (IoT):** Develops server-side applications for IoT devices, managing
communications and data processing.
3. **Scripting for Automation:** Automates repetitive tasks in software development
processes, such as testing and deployment.

![Screenshot 2024-10-19 151852.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/573ecfc2-0d41-44c8-9c19-fb3663d7c3d4/Screenshot_2024-10-19_151852.png)

**Real-Time Applications:** Efficiently manages real-time data applications, such as chat apps and live updates, using Web-Sockets.

![Screenshot 2024-10-19 151919.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/f68ddcc4-53dd-451a-b080-951663a7ab55/Screenshot_2024-10-19_151919.png)

**Desktop Applications:** Creates cross-platform desktop applications using frameworks like Electron.

![hero.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/557fd2df-c064-4cac-a90d-6ee9afdf8857/hero.png)

**Build Tools:** Powers build processes for front-end technologies using tools like:
• Webpack
• Grunt
• Gulp
• BrowSerify
• Brunch
• Yeoman

# **8. Server architecture with NodeJS**

![Screenshot 2024-10-19 152026.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/110b8e02-721a-44b4-9bc5-4da19375ca33/Screenshot_2024-10-19_152026.png)

**Nodejs server will:**

1. Create server and listen to incoming requests
2. Business logic: validation, connect to db, actual processing of data
3. Return response HTML, JSON, CSS, JS

# **First Node Server**

1. How DNS Works?
2. How Web Works?
3. What are Protocols?
4. Node Core Modules
5. Require Keyword
6. Creating first Node Server

## **1 How DNS Works?**

![Screenshot 2024-10-19 171016.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/9f1dfbac-0968-41d6-94d1-e44c2d45bbcb/Screenshot_2024-10-19_171016.png)

                                              The full form of **DNS** is the **Domain Name System**

1. **Domain Name Entry:** User types a domain (e.g., [www.example.com](http://www.example.com/)) into the browser.
2. **DNS Query:** The browser sends a DNS query to resolve the domain into an IP address.
3. **DNS Server:** Provides the correct IP address for the domain.
4. **Browser Connects:** The browser uses the IP to connect to the web server and loads the website.

## **How DNS Actually Works?**

![Screenshot 2024-10-19 171108.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/155e1485-b937-47ac-b101-ce672d572544/Screenshot_2024-10-19_171108.png)

1. **Root DNS:** Acts as the starting point for DNS resolution. It directs queries to the correct TLD server (e.g., .com, .org).
2. **TLD (Top-Level Domain) DNS:** Handles queries for specific top-level domains (e.g., .com, .net) and directs them to the authoritative DNS server (e.g., Verisign for .com, PIR for .org)
3. **Authoritative DNS:** Contains the actual IP address of the domain and answers DNS queries with this information.(e.g., Cloudflare, Google DNS).

# **2 How Web Works?**

![download.webp](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/f433de2b-648d-430f-be6d-a914cae21f13/download.webp)

1. Client Request Initiation: The client (browser) initiates a network call by entering a URL.
2. DNS Resolution: The browser contacts a DNS server to get the IP address of the domain.
3. TCP Connection: The browser establishes a TCP connection with the server's IP address.
4. HTTP Request: The browser sends an HTTP request to the server.
5. Server Processing: The server processes the request and prepares a response.
6. HTTP Response: The server sends an HTTP response back to the client.
7. Network Transmission: The response travels back to the client over the network.
8. Client Receives Response: The browser receives and interprets the response.
9. Rendering: The browser renders the content of the response and displays it to the user.

# **3 What are Protocols?**

![Screenshot 2024-10-19 171152.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/2de693e3-09ad-455c-853b-194fea37b90e/Screenshot_2024-10-19_171152.png)

Http (HyperText Transfer Protocol):
● Facilitates communication between a web browser and a server to transfer web pages.
● Sends data in plain text (no encryption).
● Used for basic website browsing without security. 

HTTPS (HyperText Transfer Protocol Secure):
● Secure version of HTTP, encrypts data for secure communication.
● Uses SSL/TLS to encrypt data.
● Used in online banking, e-commerce. 

TCP (Transmission Control Protocol):
● Ensures reliable, ordered, and error-checked data delivery over the internet.
● Establishes a connection before data is transferred.

# **4 Node Core Modules**

![Screenshot 2024-10-19 171214.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/0efc5ccd-9341-49ce-8101-2efe6e79b9b7/Screenshot_2024-10-19_171214.png)

1. Built-in: Core modules are included with Node.js installation.
2. No Installation Needed: Directly available for use without npm install.
3. Performance: Highly optimized for performance.

1. **fs (File System):** Handles file operations like reading and writing files.
2. **http:** Creates HTTP servers and makes HTTP requests.
3. **https:** Launch a SSL Server.
4. **path:** Provides utilities for handling and transforming file
5. **paths.os:** Provides operating system-related utility methods and properties.
6. **events:** Handles events and event-driven programming.
7. **crypto:** Provides cryptographic functionalities like hashing and encryption.
8. **url:** Parses and formats URL strings.

# **5 Require Keyword**

1. **Purpose:** Imports modules in Node.js.
2. **Caching:** Modules are cached after the first require call.
3. **.js** is added automatically and is not needed to at the end of module name.
4. **Path Resolution:** Node.js searches for modules in core, node_modules, and file paths.

# **What is Module?**

Module in Node.js is a simple / complex functionality organized in single or multiple JavaScript files.

**Node.js includes three types of modules:**
- Core Modules
- Local Modules
- Third Party Modules

- Node.js includes fs module to access physical file system.
- The fs module is responsible for all the asynchronous or synchronous file I/O operations.

**Synchronous:**   Loading…. Loading… you wait for it to finish….After finish you can move.
**Asynchronous:**  No Loading… No Loading … no need to wait…. you can move.

![Screenshot 2024-11-02 124525.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/e4e6b7f9-1fb5-418b-8379-8cdbefeb184a/Screenshot_2024-11-02_124525.png)

![Screenshot 2024-11-02 124622.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/f2c435bf-b85f-4f37-95ff-b8bd5c1927e5/Screenshot_2024-11-02_124622.png)

- **Understanding Synchronous Asynchronous Theory**
- **Real Example For Clear Concept**

![Screenshot 2024-11-02 124821.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/fa16fe8d-53de-4056-8a8e-a0089c35b728/Screenshot_2024-11-02_124821.png)

এই ছবিতে **Synchronous Transmission** বা **সিঙ্ক্রোনাস ট্রান্সমিশন** সম্পর্কে ধারণা দেওয়া হয়েছে।

1. **ডেটা ব্লক বা ফ্রেম আকারে পাঠানো হয়**: এখানে ডেটা ব্লক বা ফ্রেম আকারে একত্রিত করে পাঠানো হয়। একটানা ডেটা একটি নির্দিষ্ট ধারায় প্রেরণ করা হয়।
2. **Full Duplex Transmission**: এই ধরনের ট্রান্সমিশন Full Duplex অর্থাৎ, ডেটা একই সময়ে উভয় দিকেই পাঠানো ও গ্রহণ করা সম্ভব হয়।
3. **ডেটার মধ্যে কোনো গ্যাপ থাকে না**: এখানে ডেটার মাঝে কোনো বিরতি বা গ্যাপ থাকে না। এক ব্লক শেষ হওয়ার সাথে সাথেই পরের ব্লকটি শুরু হয়।
4. **সিঙ্ক্রোনাস ট্রান্সমিশন দ্রুতগতির**: এই ধরনের ট্রান্সমিশন খুব দ্রুত হয় কারণ ডেটা ধারাবাহিকভাবে পাঠানো হয়।
5. **বড় পরিমাণের ডেটা প্রেরণে কার্যকরী ও নির্ভরযোগ্য**: বড় আকারের ডেটা পাঠাতে এটি বেশি কার্যকর ও নির্ভরযোগ্য পদ্ধতি, কারণ এটি ডেটার ধারাবাহিকতা রক্ষা করে এবং দ্রুত গতিতে প্রেরণ করতে সক্ষম।

সাধারণভাবে, সিঙ্ক্রোনাস ট্রান্সমিশন বড় ডেটা এবং দ্রুতগামী প্রয়োগের জন্য উপযুক্ত যেখানে ডেটার ধারাবাহিকতা বজায় রাখতে হয়।

![Screenshot 2024-11-02 124840.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/78952e6d-4239-4c87-b4d4-415b0d93168c/Screenshot_2024-11-02_124840.png)

এই ছবিতে **Synchronous Theory** বা সিঙ্ক্রোনাস তত্ত্বের একটি উদাহরণ দেখানো হয়েছে, যেখানে সিঙ্ক্রোনাস পদ্ধতিতে ক্লায়েন্ট এবং সার্ভারের মধ্যে ডেটা লেনদেনের প্রক্রিয়া বোঝানো হয়েছে।

1. **HTTP Request এবং Response**:
    - ক্লায়েন্ট কম্পিউটার একটি **HTTP Request** পাঠায় সার্ভারের দিকে।
    - সার্ভার সেই রিকোয়েস্ট প্রক্রিয়াকরণের পরে একটি **Response** পাঠায় ক্লায়েন্টের কাছে।
2. **প্রতীক্ষার প্রয়োজন**:
    - এই প্রক্রিয়ায়, ক্লায়েন্টকে অপেক্ষা করতে হয় যতক্ষণ না সার্ভার থেকে পুরোপুরি রেসপন্স পাওয়া যায়।
    - অর্থাৎ, কোনো রিকোয়েস্ট পাঠানোর পরে, সার্ভারের প্রক্রিয়াকরণ শেষ হওয়া পর্যন্ত ক্লায়েন্ট আর অন্য কোনো কাজ করতে পারে না।
    - এই পদ্ধতিটি সিঙ্ক্রোনাস কারণ ক্লায়েন্টকে একটি কাজ শেষ না হওয়া পর্যন্ত অপেক্ষা করতে হয়।
3. **Full Page Refresh**:
    - সিঙ্ক্রোনাস পদ্ধতিতে, প্রতি রিকোয়েস্টের পরে পুরো পেজটি রিফ্রেশ হয়।
    - ক্লায়েন্ট যখন একটি অ্যাকশন (যেমন, ক্লিক) করে, তখন তাকে অপেক্ষা করতে হয় এবং পরে পুরো পেজটি রিফ্রেশ হয়।
4. **Loading এবং Waiting**:
    - ছবিতে দেখানো হয়েছে, "Loading Loading..." অর্থাৎ, ক্লায়েন্ট রিকোয়েস্ট পাঠানোর পর "লোডিং" চলতে থাকে।
    - এটি শেষ না হওয়া পর্যন্ত ব্যবহারকারীকে অপেক্ষা করতে হয়। রেসপন্স আসার পরে ব্যবহারকারী আবার কার্যক্রম চালিয়ে যেতে পারে।

### মূল পয়েন্ট:

- **Loading Loading...** : রিকোয়েস্টের পরে লোডিং চলে।
- **You wait for it to finish** : ব্যবহারকারীকে প্রক্রিয়াটি শেষ হওয়া পর্যন্ত অপেক্ষা করতে হয়।
- **After finish you can move** : প্রক্রিয়া শেষ হলে ব্যবহারকারী অন্য কাজ করতে পারে।

সাধারণভাবে, সিঙ্ক্রোনাস পদ্ধতিতে একটি কাজ সম্পন্ন হওয়া পর্যন্ত অন্য কোনো কাজ করা সম্ভব হয় না। এটি সহজ হলেও অপেক্ষার প্রয়োজন থাকায় বড় প্রজেক্ট বা জটিল কাজের জন্য কম কার্যকর।

![Screenshot 2024-11-02 124857.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/7c873ff9-a210-479a-b30f-35d5d4664f46/Screenshot_2024-11-02_124857.png)

এই ছবিতে **Asynchronous Transmission** বা অ্যাসিঙ্ক্রোনাস ট্রান্সমিশনের ধারণা দেখানো হয়েছে, যেখানে ডেটা প্রেরণের একটি নির্দিষ্ট প্রক্রিয়া ব্যাখ্যা করা হয়েছে।

1. **Half Duplex Transmission**:
    - অ্যাসিঙ্ক্রোনাস ট্রান্সমিশন **Half Duplex** ধরনের, অর্থাৎ, ডেটা একই সময়ে উভয় দিকে পাঠানো যায় না। এক সময়ে শুধু এক দিকেই ডেটা পাঠানো সম্ভব হয়।
2. **Start Bits এবং Stop Bits যুক্ত করা হয়**:
    - ডেটা প্রেরণের সময় প্রতিটি ডেটা প্যাকেটের শুরুতে একটি **Start Bit** এবং শেষে একটি **Stop Bit** যোগ করা হয়। এটি ডেটা প্রাপককে বুঝতে সাহায্য করে কখন ডেটা শুরু হচ্ছে এবং কখন শেষ হচ্ছে।
3. **ডেটা বাইট বা ক্যারেক্টার আকারে পাঠানো হয়**:
    - অ্যাসিঙ্ক্রোনাস ট্রান্সমিশনে ডেটা বাইট বা ক্যারেক্টার আকারে প্রেরণ করা হয়, অর্থাৎ ছোট ছোট ডেটা ইউনিটে বিভক্ত করে পাঠানো হয়।
4. **ধীর গতিসম্পন্ন**:
    - এই পদ্ধতিতে ট্রান্সমিশন তুলনামূলকভাবে ধীর, কারণ প্রতিটি বাইটের আগে ও পরে স্টার্ট এবং স্টপ বিট থাকে যা ট্রান্সমিশনের গতি কমিয়ে দেয়।
5. **ডেটার মধ্যে গ্যাপ থাকে**:
    - এখানে ডেটার মধ্যে গ্যাপ বা বিরতি থাকে, যার মানে প্রতিটি বাইটের মধ্যে কিছু বিরতি থেকে যায়। এই গ্যাপের কারণে ডেটা প্রেরণে সময় লাগে।

### মূল পয়েন্ট:

- **এই ট্রান্সমিশনটি হাফ ডুপ্লেক্স প্রকারের**: অর্থাৎ, একবারে এক দিকেই ডেটা প্রেরণ সম্ভব।
- **স্টার্ট ও স্টপ বিট যুক্ত করা হয়**: ডেটা প্যাকেটের শুরুতে ও শেষে বিট যোগ করা হয়।
- **ডেটা বাইট বা ক্যারেক্টার আকারে পাঠানো হয়**: ছোট আকারে ডেটা পাঠানো হয়।
- **অ্যাসিঙ্ক্রোনাস ট্রান্সমিশন ধীরগতির**: এই পদ্ধতিতে ট্রান্সমিশন ধীর হয়।
- **ডেটার মধ্যে গ্যাপ থাকে**: প্রতিটি ডেটা প্যাকেটের মাঝে বিরতি থাকে।

অ্যাসিঙ্ক্রোনাস ট্রান্সমিশন সাধারণত ছোট ডেটা প্যাকেট পাঠানোর জন্য ব্যবহৃত হয়, যেখানে উচ্চ গতির প্রয়োজন হয় না।

![Screenshot 2024-11-02 124914.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5a4b045f-ac19-493c-832a-3cb357cda128/9327618a-9e76-4f7b-a2af-1eec0e1b08a6/Screenshot_2024-11-02_124914.png)

এই ছবিটি অ্যাসিঙ্ক্রোনাস থিয়োরি (Asynchronous Theory) নিয়ে আলোচনা করছে, বিশেষ করে জাভাস্ক্রিপ্ট এবং Node.js-এর ক্ষেত্রে। এখানে দেখানো হয়েছে যে কীভাবে অ্যাসিঙ্ক্রোনাস প্রক্রিয়া কাজ করে।

1. **উপরের অংশে** ক্লায়েন্ট কম্পিউটার থেকে একটি HTTP অনুরোধ (Request) পাঠানো হচ্ছে এবং সার্ভার থেকে একটি প্রতিক্রিয়া (Response) ফেরত পাঠানো হচ্ছে। এতে অ্যাসিঙ্ক্রোনাস প্রক্রিয়ার সুবিধাগুলো উল্লেখ করা হয়েছে, যেমন:
    - **লোডিং নেই** – পুরো পৃষ্ঠা পুনরায় লোড না করেই ডেটা আপডেট হয়।
    - **অপেক্ষার প্রয়োজন নেই** – ব্যবহারকারীকে অপেক্ষা করতে হয় না, কারণ সার্ভার থেকে ডেটা আসতে সময় নিলেও ব্যবহারকারী অন্য কাজ করতে পারে।
    - **আপনি চলতে পারেন** – ব্যবহারকারী ইন্টারফেসটি প্রতিক্রিয়াশীল থাকে, ফলে ব্যবহারকারীর কাজের গতি অব্যাহত থাকে।
2. **নিচের অংশে** অ্যাসিঙ্ক্রোনাস কার্যপ্রণালীর ধাপগুলো দেখানো হয়েছে:
    - **ক্লায়েন্ট** সেকশনে, ব্যবহারকারীর ইন্টারফেস (UI) এবং ব্যবহারকারীর ইভেন্টগুলি দেখানো হয়েছে।
    - একটি **AJAX ইঞ্জিন** রয়েছে, যা অ্যাসিঙ্ক্রোনাস ডেটা ট্রান্সফার পরিচালনা করে।
    - **সার্ভার** সেকশনে, সার্ভার-সাইড প্রসেসিং এবং ডেটা ট্রান্সফার চিত্রিত করা হয়েছে।

এটি মূলত বোঝাচ্ছে যে অ্যাসিঙ্ক্রোনাস প্রক্রিয়ায়, সার্ভার এবং ক্লায়েন্টের মধ্যে ডেটা আদান-প্রদান অবিরত চলতে পারে, তবে ব্যবহারকারী ইন্টারফেস প্রতিক্রিয়াশীল থাকে এবং ব্যবহারকারীরা অন্য কাজ চালিয়ে যেতে পারে।

# **FS Module**

### **fs read file Asynchronous**

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

# **Fs File Write**

```jsx
const fs = require('fs');
const http = require('http');

const server = http.createServer((req, res) => {
    if (req.url === "/") {
        fs.writeFile('newFile.txt', 'Welcome to Node JS', function (error) {
            if (error) {
                res.writeHead(200, { 'Content-Type': 'text/html' });
                res.write("File Write Fail");
                res.end();
            } else {
                res.writeHead(200, { 'Content-Type': 'text/html' });
                res.write("File Write Success");
                res.end();
            }
        });
    }
});

server.listen(3030);
console.log("Server Run Success");

```

### কোড ব্যাখ্যা (বাংলায়):

1. **মডিউল ইম্পোর্ট (Modules Import):**
    
    ```jsx
    const fs = require('fs');
    const http = require('http');
    ```
    
    - `fs`: Node.js এর ফাইল সিস্টেম মডিউল, যা ফাইল তৈরি, পড়া, লেখা এবং মুছতে ব্যবহৃত হয়।
    - `http`: Node.js এর HTTP মডিউল, যা HTTP সার্ভার তৈরি করতে ব্যবহৃত হয়।
2. **সার্ভার তৈরি করা (Creating the Server):**
    
    ```jsx
    javascript
    Copy code
    const server = http.createServer((req, res) => {
    
    ```
    
    - `http.createServer`: এটি একটি নতুন HTTP সার্ভার তৈরি করে। সার্ভারটি ক্লায়েন্টের রিকুয়েস্ট পাওয়ার সময় একটি ফাংশন কল করে, যেখানে `req` (রিকুয়েস্ট) এবং `res` (রেসপন্স) প্যারামিটার হিসেবে ব্যবহৃত হয়।
3. **রিকুয়েস্ট URL চেক করা (Checking the Request URL):**
    
    ```jsx
    f (req.url === "/") {
    
    ```
    
    - এই অংশে পরীক্ষা করা হচ্ছে যে ক্লায়েন্টের রিকুয়েস্টের URL হল `/` কিনা। অর্থাৎ, হোম পেজে রিকুয়েস্ট করা হয়েছে কি না।
4. **ফাইল লেখা (Writing to the File):**
    
    ```jsx
    fs.writeFile('newFile.txt', 'Welcome to Node JS', function (error) {
    ```
    
    - `fs.writeFile`: এটি একটি অ্যাসিনক্রোনাস (Asynchronous) মেথড যা একটি নতুন ফাইল তৈরি করে এবং এতে নির্দিষ্ট টেক্সট লিখে। এখানে `newFile.txt` ফাইলের নাম এবং `'Welcome to Node JS'` হল লেখা।
    - `function (error)`: ফাইল লেখার প্রক্রিয়া সম্পন্ন হলে এই ফাংশনটি কল হয়। যদি ফাইল লেখার সময় কোনো সমস্যা হয়, `error` প্যারামিটারটি সেট হবে।
5. **এরর হ্যান্ডলিং (Handling Errors):**
    
    ```jsx
    if (error) {
        res.writeHead(200, { 'Content-Type': 'text/html' });
        res.write("File Write Fail");
        res.end();
    }
    ```
    
    - যদি কোনো ত্রুটি ঘটে (যেমন ফাইল তৈরি করতে ব্যর্থ হয়), তাহলে সার্ভার একটি HTTP রেসপন্স পাঠায়, যেখানে ২০০ স্ট্যাটাস কোড সহ "File Write Fail" বার্তা থাকে।
    - `res.writeHead(200)`: HTTP রেসপন্সের হেডার সেট করে।
    - `res.write("File Write Fail")`: ক্লায়েন্টকে ফাইল লেখার ব্যর্থতার বার্তা পাঠায়।
    - `res.end()`: রেসপন্স শেষ করে।
6. **ফাইল সফলভাবে লেখা হলে (On Successful File Write):**
    
    ```jsx
    else {
        res.writeHead(200, { 'Content-Type': 'text/html' });
        res.write("File Write Success");
        res.end();
    }
    
    ```
    
    - যদি ফাইল সফলভাবে লেখা হয়, তাহলে সার্ভার ২০০ স্ট্যাটাস কোড সহ "File Write Success" বার্তা পাঠায়।
    - একইভাবে, HTTP রেসপন্সের হেডার, লেখার বার্তা এবং রেসপন্স শেষ করার কার্যক্রম চলে।
7. **সার্ভার লিসেনিং শুরু করা (Server Listening):**
    
    ```jsx
    server.listen(3030);
    console.log("Server Run Success");
    ```
    
    - `server.listen(3030)`: সার্ভারটি পোর্ট ৩০৩০-এ ক্লায়েন্টের রিকুয়েস্ট শোনার জন্য প্রস্তুত।
    - `console.log("Server Run Success")`: সার্ভার সফলভাবে চালু হলে এটি কনসোলে "Server Run Success" বার্তা প্রিন্ট করবে।

### সংক্ষেপে:

এই কোডটি একটি Node.js HTTP সার্ভার তৈরি করে, যা `/` URL এ রিকুয়েস্ট আসলে `newFile.txt` নামে একটি নতুন ফাইল তৈরি করে এবং তাতে "Welcome to Node JS" লেখে। যদি ফাইল লেখার সময় কোনো সমস্যা হয়, তাহলে "File Write Fail" বার্তা ক্লায়েন্টকে পাঠায়; অন্যথায়, "File Write Success" বার্তা পাঠানো হয়।

# **Fs File Write** *Synchronous*

```jsx
const fs = require('fs');
const http = require('http');

const server = http.createServer((req,res) =>{
    //Synchronous
    if(req.url==="/"){

        let error = fs.writeFileSync('newSync.txt','Welcome to File Sync');

        if(error){
            res.writeHead(200,{'Content-Type':'text/html'});
            res.write("File Write Fail");
            res.end();
        }
        else{
            res.writeHead(200,{'Content-Type':'text/html'});
            res.write("File Write Success");
            res.end();
        }
    }
});

server.listen(4030);
console.log("Server Run Success");
```

### কোড ব্যাখ্যা (বাংলায়):

1. **মডিউল ইম্পোর্ট (Modules Import):**
    
    ```jsx
    const fs = require('fs');
    const http = require('http');
    ```
    
    - `fs`: Node.js এর ফাইল সিস্টেম মডিউল, যা ফাইল তৈরি, পড়া, লেখা এবং মুছতে ব্যবহৃত হয়।
    - `http`: Node.js এর HTTP মডিউল, যা HTTP সার্ভার তৈরি করতে ব্যবহৃত হয়।
2. **সার্ভার তৈরি করা (Creating the Server):**
    
    ```jsx
    const server = http.createServer((req, res) => {
    ```
    
    - `http.createServer`: এটি একটি নতুন HTTP সার্ভার তৈরি করে। সার্ভারটি ক্লায়েন্টের রিকুয়েস্ট পাওয়ার সময় একটি ফাংশন কল করে, যেখানে `req` (রিকুয়েস্ট) এবং `res` (রেসপন্স) প্যারামিটার হিসেবে ব্যবহৃত হয়।
3. **রিকুয়েস্ট URL চেক করা (Checking the Request URL):**
    
    ```jsx
    if (req.url === "/") {
    ```
    
    - এখানে পরীক্ষা করা হচ্ছে যে ক্লায়েন্টের রিকুয়েস্টের URL হল `/` কিনা। অর্থাৎ, ক্লায়েন্ট যদি সার্ভারের হোম পেজে রিকুয়েস্ট করে, তাহলে এই কোডটি এক্সিকিউট হবে।
4. **সিঙ্ক্রোনাস ফাইল লেখা (Synchronous File Writing):**
    
    ```jsx
    let error = fs.writeFileSync('newSync.txt', 'Welcome to File Sync')
    ```
    
    - `fs.writeFileSync`: এটি একটি সিঙ্ক্রোনাস (Synchronous) মেথড যা একটি নতুন ফাইল তৈরি করে এবং তাতে নির্দিষ্ট টেক্সট লেখে। এখানে `newSync.txt` ফাইলের নাম এবং `'Welcome to File Sync'` হল লেখা।
    - এই মেথডটি ফাইল লেখার সময় কোনো সমস্যা হলে একটি ত্রুটি (error) রিটার্ন করে। যেহেতু এটি সিঙ্ক্রোনাস, তাই এটি সম্পন্ন না হওয়া পর্যন্ত পরবর্তী কোডগুলি এক্সিকিউট হয় না।
5. **এরর হ্যান্ডলিং (Handling Errors):**
    
    ```jsx
    if(error) {
        res.writeHead(200, { 'Content-Type': 'text/html' });
        res.write("File Write Fail");
        res.end();
    }
    ```
    
    - যেহেতু `writeFileSync` একটি ত্রুটি ফেরত দেয় না, তাই এখানে `if (error)` অংশ কখনোই true হবে না। সুতরাং, `error` চেক করার জন্য এখানে সঠিক পদ্ধতি নয়।
    - যদি ফাইল লেখার সময় কোনো সমস্যা ঘটে (যেমন ফাইল লেখার অনুমতি নেই), তাহলে সার্ভার ২০০ স্ট্যাটাস কোড সহ "File Write Fail" বার্তা পাঠায়। কিন্তু এখানে সমস্যাটি হবে কারণ `writeFileSync` কখনোই `error` রিটার্ন করে না।
6. **ফাইল সফলভাবে লেখা হলে (On Successful File Write):**
    
    ```jsx
    else {
        res.writeHead(200, { 'Content-Type': 'text/html' });
        res.write("File Write Success");
        res.end();
    }
    ```
    
    - যেহেতু `fs.writeFileSync` ত্রুটি রিটার্ন করে না, তাই এখানে `else` ব্লকটি সর্বদা এক্সিকিউট হবে, এবং সার্ভার ২০০ স্ট্যাটাস কোড সহ "File Write Success" বার্তা পাঠাবে।
7. **সার্ভার লিসেনিং শুরু করা (Server Listening):**
    
    ```jsx
    srver.listen(4030);
    console.log("Server Run Success");
    ```
    
    - `server.listen(4030)`: সার্ভারটি পোর্ট ৪০৩০-এ ক্লায়েন্টের রিকুয়েস্ট শোনার জন্য প্রস্তুত।
    - `console.log("Server Run Success")`: সার্ভার সফলভাবে চালু হলে এটি কনসোলে "Server Run Success" বার্তা প্রিন্ট করবে।

### সংক্ষেপে:

এই কোডটি একটি Node.js HTTP সার্ভার তৈরি করে, যা `/` URL এ রিকুয়েস্ট আসলে `newSync.txt` নামে একটি নতুন ফাইল তৈরি করে এবং তাতে "Welcome to File Sync" লেখে। যেহেতু `writeFileSync` কখনো ত্রুটি রিটার্ন করে না, তাই "File Write Fail" বার্তা পাঠানো হবে না, বরং "File Write Success" বার্তা সর্বদা পাঠানো হবে।

# Fs File Rename Async

```jsx
const fs = require('fs');
const http = require('http');

const server = http.createServer((req,res) => {
    //Async
    if(req.url==="/"){
        
        fs.rename('oldFile.txt','newFile',function(error){

            if(error){
                res.writeHead(200,{'Content-Type':'text/html'});
                res.write("File name Fail");
                res.end();
            }
            else{
                res.writeHead(200,{'Content-Type':'text/html'});
                res.write("File name Success");
                res.end();
            }
        })
    }
});

server.listen(3020);
console.log("Server Run Success");
```

এই কোডটি একটি Node.js সার্ভার তৈরি করে যা HTTP অনুরোধ গ্রহণ করে এবং একটি ফাইলের নাম পরিবর্তন করে। নিচে পুরো কোডটি বাংলায় ব্যাখ্যা করা হলো:

```jsx
const fs = require('fs');
const http = require('http');
```

প্রথমে, আমরা `fs` (File System) এবং `http` মডিউলগুলো `require()` ফাংশনের মাধ্যমে আমদানি করেছি। `fs` মডিউল ফাইল সিস্টেমের সাথে কাজ করার জন্য এবং `http` মডিউল HTTP সার্ভার তৈরি করার জন্য ব্যবহৃত হয়।

```jsx
const server = http.createServer((req,res) => {
```

`http.createServer()` ফাংশনটি একটি HTTP সার্ভার তৈরি করে, যেখানে আমরা একটি ফাংশন পাস করেছি যা প্রতি অনুরোধের জন্য কল করা হবে। ফাংশনের দুইটি প্যারামিটার আছে:

- `req` (অনুরোধ): ক্লায়েন্ট থেকে আসা অনুরোধের তথ্য।
- `res` (প্রতিক্রিয়া): সার্ভার থেকে ক্লায়েন্টে পাঠানো প্রতিক্রিয়া।

```jsx
if(req.url==="/"){

```

এখানে চেক করা হচ্ছে যে অনুরোধের URL "/" (মূল পাতা) কিনা। যদি `/` হয়, তবে পরবর্তী অংশটি কার্যকর হবে।

```jsx
fs.rename('oldFile.txt','newFile',function(error){
```

`fs.rename()` ফাংশনটি ব্যবহার করা হয়েছে `oldFile.txt` ফাইলের নাম পরিবর্তন করে `newFile` নাম দেওয়ার জন্য। এটি একটি অ্যাসিঙ্ক্রোনাস ফাংশন, অর্থাৎ এটি পটভূমিতে কাজ করে এবং সম্পন্ন হলে একটি কলব্যাক ফাংশন চালায়। কলব্যাক ফাংশনের মধ্যে একটি প্যারামিটার আছে `error`, যা কোনো সমস্যা হলে সেটিকে সংরক্ষণ করে।

```jsx
if(error){
   res.writeHead(200,{'Content-Type':'text/html'});
   res.write("File name Fail");
   res.end();
 }
```

যদি নাম পরিবর্তন করার সময় কোনো ত্রুটি ঘটে, তাহলে `error` ভেরিয়েবলটি সেট হবে। এই ক্ষেত্রে, সার্ভার `200` স্ট্যাটাস কোড সহ একটি প্রতিক্রিয়া পাঠায় এবং "File name Fail" বার্তাটি ক্লায়েন্টকে দেখায়।

```jsx
else{
     res.writeHead(200,{'Content-Type':'text/html'});
         res.write("File name Success");
          res.end();
           }
        })
    }
});
```

যদি কোনো ত্রুটি না ঘটে, তবে `else` অংশ কার্যকর হবে, এবং সার্ভার ক্লায়েন্টকে "File name Success" বার্তা পাঠাবে। এখানে `res.end()` ফাংশনটি প্রতিক্রিয়া শেষ করে।

```jsx
server.listen(3020);
console.log("Server Run Success");
```

`server.listen(3020)` ফাংশনটি সার্ভারকে `3020` পোর্টে চালু করে, এবং `console.log("Server Run Success")` মেসেজটি কনসোলে প্রিন্ট করে জানায় যে সার্ভারটি সফলভাবে চালু হয়েছে।

### সারসংক্ষেপে:

এই সার্ভারটি যখন `/` URL-এ অনুরোধ পায়, তখন এটি `oldFile.txt` ফাইলটির নাম পরিবর্তন করে `newFile` রাখার চেষ্টা করে। যদি নাম পরিবর্তন সফল হয়, এটি "File name Success" বার্তা পাঠায়, অন্যথায় "File name Fail" বার্তা পাঠায়।

# **Fs File Rename Sync**

```jsx
const fs = require('fs');
const http = require('http');

const server = http.createServer((req,res) => {
    //Sync
    if(req.url==="/"){
        
        try {
            let result = fs.renameSync('oldFileSync.txt','newFileSync.txt');

            res.writeHead(200,{'Content-Type':'text/html'});
            res.write("File Rename Success");
            res.end();
        } catch (error) {
            res.writeHead(200,{'Content-Type':'text/html'});
            res.write("File Rename Fail: " + error.message);
            res.end();
        }
    }
});

server.listen(3010);
console.log("Server Run Success");
```

এই কোডটি Node.js ব্যবহার করে একটি HTTP সার্ভার তৈরি করে, যা ফাইল রিনেম (নাম পরিবর্তন) করার জন্য একটি সিঙ্ক্রোনাস (Sync) ফাংশন ব্যবহার করছে। পুরো কোডটি বাংলায় ব্যাখ্যা করা হলো:

### 1. **মডিউল আমদানি (Importing Modules):**

```jsx
const fs = require('fs');
const http = require('http');
```

- এখানে `fs` মডিউল ফাইল সিস্টেমের সাথে কাজ করার জন্য ব্যবহৃত হয়, যা ফাইল তৈরি, মুছে ফেলা, নাম পরিবর্তন করার মতো কাজ করতে সহায়ক।
- `http` মডিউল HTTP সার্ভার তৈরি করার জন্য ব্যবহৃত হয়।

### 2. **HTTP সার্ভার তৈরি করা:**

```jsx
const server = http.createServer((req, res) => {
    //Sync
    if(req.url==="/"){
```

- এখানে `http.createServer()` ফাংশনটি ব্যবহার করে একটি সার্ভার তৈরি করা হয়েছে। `req` এবং `res` হলো দুটি প্যারামিটার, যেখানে `req` (request) ক্লায়েন্টের থেকে আসা অনুরোধ, এবং `res` (response) সার্ভার থেকে ক্লায়েন্টে পাঠানো উত্তর।
- যখন URL `/` (মূল পাথ) এর অনুরোধ করা হয়, তখন ফাইলের নাম পরিবর্তনের প্রক্রিয়া শুরু হবে।

### 3. **ফাইলের নাম পরিবর্তন করা (Sync Mode):**

```jsx
try {
    let result = fs.renameSync('oldFileSync.txt','newFileSync.txt');
```

- এখানে `fs.renameSync()` ফাংশনটি একটি সিঙ্ক্রোনাস ফাংশন, যা তৎক্ষণাৎ কাজ শেষ না করা পর্যন্ত সার্ভারের অন্য কোনো কাজ হবে না। এটি 'oldFileSync.txt' ফাইলটির নাম পরিবর্তন করে 'newFileSync.txt' করার চেষ্টা করে।
- `try-catch` ব্লক ব্যবহার করা হয়েছে, যাতে কোনো সমস্যা হলে সেটা হ্যান্ডেল করা যায় এবং সার্ভার ক্র্যাশ না করে।

### 4. **সফল হলে উত্তর পাঠানো:**

```jsx
res.writeHead(200,{'Content-Type':'text/html'});
res.write("File Rename Success");
res.end();
```

- যদি ফাইলের নাম সফলভাবে পরিবর্তন হয়, তাহলে সার্ভার ২০০ স্ট্যাটাস কোড সহ একটি সফল বার্তা ("File Rename Success") ক্লায়েন্টকে পাঠায়।

### 5. **ত্রুটি হলে উত্তর পাঠানো:**

```jsx
} catch (error) {
    res.writeHead(200,{'Content-Type':'text/html'});
    res.write("File Rename Fail: " + error.message);
    res.end();
}
```

- যদি কোনো ত্রুটি ঘটে (যেমন ফাইলটি বিদ্যমান না থাকা), তাহলে `catch` ব্লকে ঢুকে একটি ত্রুটির বার্তা ক্লায়েন্টকে পাঠানো হয়। `error.message` অংশটি ত্রুটির প্রকৃত কারণটি দেখায়।

### 6. **সার্ভার চালু করা:**

```jsx
server.listen(3010);
console.log("Server Run Success");
```

- অবশেষে, `server.listen(3010)` ফাংশনটি সার্ভারকে ৩০১০ পোর্টে চালু করে।
- `console.log("Server Run Success")` এটি কনসোল বা টার্মিনালে বার্তা প্রদর্শন করে জানায় যে সার্ভার সফলভাবে চলছে।

### সারসংক্ষেপ:

এই কোডটি মূলত একটি সার্ভার তৈরি করে, যা একটি নির্দিষ্ট URL থেকে অনুরোধ পেলে একটি ফাইলের নাম পরিবর্তন করার চেষ্টা করে। যদি ফাইলটির নাম সফলভাবে পরিবর্তন হয়, তাহলে "File Rename Success" বার্তা প্রদর্শিত হয়। অন্যথায়, যদি কোনো ত্রুটি ঘটে, "File Rename Fail" বার্তা এবং ত্রুটির কারণ দেখানো হয়।

# **FS File Delete Async**

```jsx
const fs = require('fs');
const http = require('http');

const server = http.createServer((req,res) => {
    //Async
    if(req.url==="/"){
        
        fs.unlink('newDemo.txt',function(error){

            if(error){
                res.writeHead(200,{'Content-Type':'text/html'});
                res.write("File Delete Fail");
                res.end();
            }
            else{
                res.writeHead(200,{'Content-Type':'text/html'});
                res.write("File Delete Success");
                res.end();
            }
        })
    }
});

server.listen(3020);
console.log("Server Run Success");
```

এই কোডটি Node.js ব্যবহার করে একটি HTTP সার্ভার তৈরি করেছে, যা নির্দিষ্ট URL-এ অনুরোধ আসলে `newDemo.txt` নামের ফাইলটি অ্যাসিঙ্ক্রোনাসভাবে (অপ্রতীক্ষিতভাবে) ডিলিট করার চেষ্টা করে।

### কোডের বিশ্লেষণ:

```jsx
const fs = require('fs');
const http = require('http');
```

- **`fs`** মডিউলটি ফাইল পরিচালনার জন্য ব্যবহৃত হয়, যেমন ফাইল তৈরি, পড়া, ডিলিট করা ইত্যাদি।
- **`http`** মডিউলটি HTTP সার্ভার তৈরি করতে ব্যবহৃত হয়।

```jsx
const server = http.createServer((req,res) => {
    //Async
    if(req.url==="/"){

        fs.unlink('newDemo.txt',function(error){

            if(error){
                res.writeHead(200,{'Content-Type':'text/html'});
                res.write("File Delete Fail");
                res.end();
            }
            else{
                res.writeHead(200,{'Content-Type':'text/html'});
                res.write("File Delete Success");
                res.end();
            }
        })
    }
});
```

- **`http.createServer`**: এটি একটি সার্ভার তৈরি করে, যা অনুরোধ (`req`) এবং প্রতিক্রিয়া (`res`) গ্রহণ করে।
- **`req.url === "/"`**: চেক করে যে ব্যবহারকারী মূল রুট URL এ ("/") অনুরোধ পাঠিয়েছে কিনা।

### ফাইল ডিলিট করা:

- **`fs.unlink('newDemo.txt', function(error){ ... })`**: এই মেথডটি `newDemo.txt` ফাইলটি অ্যাসিঙ্ক্রোনাসভাবে ডিলিট করার চেষ্টা করে।
    - **`error` প্যারামিটার**: যদি ফাইল ডিলিট করতে কোনো সমস্যা হয়, তাহলে `error` প্যারামিটারে ত্রুটির তথ্য থাকবে।

### রেসপন্স অংশ:

- যদি **ত্রুটি** ঘটে, তাহলে:
    - **`res.writeHead(200,{'Content-Type':'text/html'})`**: এই লাইনটি HTTP স্ট্যাটাস কোড 200 এবং কন্টেন্ট টাইপ `text/html` সেট করে।
    - **`res.write("File Delete Fail")`**: "File Delete Fail" বার্তাটি ক্লায়েন্টকে পাঠানো হয়।
    - **`res.end()`**: প্রতিক্রিয়া বন্ধ করে।
- যদি **সফল হয়** (ত্রুটি না ঘটে), তাহলে:
    - **`res.write("File Delete Success")`**: "File Delete Success" বার্তাটি ক্লায়েন্টকে পাঠানো হয়।
    - **`res.end()`**: প্রতিক্রিয়া বন্ধ করে।

```jsx
srver.listen(3020);
console.log("Server Run Success");
```

- **`server.listen(3020)`**: সার্ভারটি পোর্ট 3020 এ শোনার জন্য প্রস্তুত থাকে।
- **`console.log("Server Run Success")`**: কনসোলে "Server Run Success" বার্তা প্রদর্শিত হয়, যা নির্দেশ করে যে সার্ভার সফলভাবে চলছে।

### সংক্ষেপে:

এই কোডটি একটি HTTP সার্ভার তৈরি করে যা পোর্ট 3020 এ চলবে। যখনই ব্যবহারকারী মূল রুট (`/`) এ অনুরোধ পাঠায়, সার্ভারটি `newDemo.txt` ফাইলটি অ্যাসিঙ্ক্রোনাসভাবে ডিলিট করার চেষ্টা করে। যদি ফাইল ডিলিট সফল হয়, তাহলে "File Delete Success" মেসেজ পাঠায়; অন্যথায়, "File Delete Fail" মেসেজ পাঠায়।

# **FS File Delete Synchronous**

```jsx
const fs = require('fs');
const http = require('http');

const server = http.createServer((req, res) => {
    // Synchronous
    if (req.url === "/") {
        try {
            fs.unlinkSync('demoFile.txt'); // Properly call unlinkSync to delete the file
            res.writeHead(200, { 'Content-Type': 'text/html' });
            res.write("File Delete Success");
            res.end();
        } catch (error) {
            res.writeHead(500, { 'Content-Type': 'text/html' }); // 500 Internal Server Error
            res.write("File Delete Fail: " + error.message);
            res.end();
        }
    }
});

server.listen(3030);
console.log("Server Run Success");

```

এই কোডটি একটি HTTP সার্ভার তৈরি করে যা একটি নির্দিষ্ট URL-এ ("/") একটি ফাইল মুছে ফেলার কাজ করে। নিচে কোডের প্রতিটি অংশের বাংলা ব্যাখ্যা দেওয়া হল:

```jsx
const fs = require('fs');
const http = require('http');
```

- **`const fs = require('fs');`**: এটি Node.js এর ফাইল সিস্টেম মডিউল `fs` কে অন্তর্ভুক্ত করে, যা ফাইল এবং ডিরেক্টরি ম্যানিপুলেশনের জন্য ব্যবহৃত হয়।
- **`const http = require('http');`**: এটি Node.js এর HTTP মডিউলকে অন্তর্ভুক্ত করে, যা HTTP সার্ভার তৈরি করতে ব্যবহৃত হয়।

```jsx
const server = http.createServer((req, res) => {
```

- **`const server = http.createServer(...);`**: এটি একটি HTTP সার্ভার তৈরি করে। সার্ভারটি `req` (অনুরোধ) এবং `res` (প্রতিক্রিয়া) নামক দুটি প্যারামিটার গ্রহণ করে।

```jsx
 if (req.url === "/") {
```

- **`if (req.url === "/") {`**: এই শর্তটি পরীক্ষা করে যে ব্যবহারকারীর অনুরোধের URL টি "/" কিনা। যদি তাই হয়, তাহলে নিচের কোড ব্লকটি কার্যকর হবে।

```jsx
try {
     fs.unlinkSync('demoFile.txt'); // Properly call unlinkSync to delete the file
```

- **`try { ... }`**: `try` ব্লকটি চেষ্টা করে দেখবে যে কোডের ভিতরের নির্দেশনাগুলি সফলভাবে কার্যকর হয় কিনা।
- **`fs.unlinkSync('demoFile.txt');`**: এটি `demoFile.txt` নামের ফাইলটি সিঙ্ক্রোনাসভাবে মুছে ফেলার চেষ্টা করে। যদি ফাইলটি সফলভাবে মুছে যায়, তাহলে পরবর্তী অংশ কার্যকর হবে।

```jsx
res.writeHead(200, { 'Content-Type': 'text/html' });
res.write("File Delete Success");
res.end();
```

- **`res.writeHead(200, { 'Content-Type': 'text/html' });`**: এটি সার্ভার থেকে 200 (সফল) স্ট্যাটাস কোড এবং কন্টেন্ট টাইপ হিটেমপ্লেট নির্দেশ করে।
- **`res.write("File Delete Success");`**: ব্যবহারকারীকে একটি বার্তা পাঠায়, যা বলে "ফাইল সফলভাবে মুছে ফেলা হয়েছে"।
- **`res.end();`**: এই লাইনটি প্রতিক্রিয়াটি শেষ করে এবং ক্লায়েন্টের কাছে পাঠায়।

```jsx
} catch (error) {
       res.writeHead(500, { 'Content-Type': 'text/html' }); // 500 Internal Server Error
       res.write("File Delete Fail: " + error.message);
       res.end();
}
```

- **`catch (error) { ... }`**: যদি `try` ব্লকের ভিতরে কোনো সমস্যা হয়, তবে এটি `catch` ব্লকে চলে যাবে।
- **`res.writeHead(500, { 'Content-Type': 'text/html' });`**: এটি সার্ভার থেকে 500 (অভ্যন্তরীণ সার্ভার ত্রুটি) স্ট্যাটাস কোড পাঠায়।
- **`res.write("File Delete Fail: " + error.message);`**: এটি ব্যবহারকারীকে জানায় যে ফাইল মুছতে ব্যর্থ হয়েছে এবং ত্রুটির বার্তা দেখায়।
- **`res.end();`**: এই লাইনটি প্রতিক্রিয়াটি শেষ করে।

```jsx
server.listen(3030);
console.log("Server Run Success");
```

- **`server.listen(3030);`**: সার্ভারটি 3030 পোর্টে শোনার জন্য প্রস্তুত হয়।
- **`console.log("Server Run Success");`**: সার্ভারটি সফলভাবে চালু হলে এটি কনসোলে একটি বার্তা প্রদর্শন করে।

এভাবে, এই কোডটি একটি HTTP সার্ভার তৈরি করে যা একটি নির্দিষ্ট URL-এ ফাইল মুছে ফেলার চেষ্টা করে এবং সফল বা ব্যর্থ হলে ব্যবহারকারীকে সঠিক বার্তা প্রদান করে।

# **FS File Exists Async**

```jsx
const fs = require('fs');
const http = require('http');

const server = http.createServer((req,res) => {
    //Async
    if(req.url==="/"){
        
        fs.exists('newDemo.txt',function(error){

            if (error) {
                res.end(` File Exist`);
            } else {
                res.end(`File Does not exist`);
            }
        })
    }
});

// OutPut :- File Exist

server.listen(3020);
console.log("Server Run Success"); 
```

এই কোডটি একটি HTTP সার্ভার তৈরি করে যা একটি নির্দিষ্ট URL ("/") এ একটি ফাইলের অস্তিত্ব পরীক্ষা করে। নিচে কোডের প্রতিটি অংশের বাংলা ব্যাখ্যা দেওয়া হল:

```jsx
const fs = require('fs');
const http = require('http');
```

- **`const fs = require('fs');`**: এটি Node.js এর ফাইল সিস্টেম মডিউল `fs` কে অন্তর্ভুক্ত করে, যা ফাইল এবং ডিরেক্টরি ম্যানিপুলেশনের জন্য ব্যবহৃত হয়।
- **`const http = require('http');`**: এটি Node.js এর HTTP মডিউলকে অন্তর্ভুক্ত করে, যা HTTP সার্ভার তৈরি করতে ব্যবহৃত হয়।

```jsx
const server = http.createServer((req, res) => {
```

- **`const server = http.createServer(...);`**: এটি একটি HTTP সার্ভার তৈরি করে। সার্ভারটি `req` (অনুরোধ) এবং `res` (প্রতিক্রিয়া) নামক দুটি প্যারামিটার গ্রহণ করে।

```jsx
    if (req.url === "/") {
```

- **`if (req.url === "/") {`**: এই শর্তটি পরীক্ষা করে যে ব্যবহারকারীর অনুরোধের URL টি "/" কিনা। যদি তাই হয়, তাহলে নিচের কোড ব্লকটি কার্যকর হবে।

```jsx
        fs.exists('newDemo.txt', function(error) {
```

- **`fs.exists('newDemo.txt', function(error) { ... });`**: এই লাইনটি `newDemo.txt` নামের ফাইলটির অস্তিত্ব পরীক্ষা করে। `fs.exists` একটি অ্যাসিঙ্ক্রোনাস ফাংশন, যা প্রথম প্যারামিটার হিসেবে ফাইলের নাম এবং দ্বিতীয় প্যারামিটার হিসেবে একটি কলব্যাক ফাংশন গ্রহণ করে। ফাইলটি যদি বিদ্যমান থাকে, তবে `error` প্যারামিটার `null` হবে; অন্যথায়, এটি একটি ত্রুটি অবজেক্ট হবে।

```jsx
            if (error) {
                res.end(` File Exist`);
            } else {
                res.end(`File Does not exist`);
            }
```

- **`if (error) { ... }`**: যদি `error` প্যারামিটার `null` না হয় (অর্থাৎ, ফাইলটি বিদ্যমান নয়), তবে এই ব্লকটি কার্যকর হবে।
    - **`res.end(` File Exist`);`**: এটি সার্ভার থেকে ক্লায়েন্টকে পাঠায় যে ফাইলটি বিদ্যমান।
- **`else { ... }`**: যদি `error` প্যারামিটার `null` হয় (অর্থাৎ, ফাইলটি বিদ্যমান), তাহলে এই ব্লকটি কার্যকর হবে।
    - **`res.end(`File Does not exist`);`**: এটি সার্ভার থেকে ক্লায়েন্টকে পাঠায় যে ফাইলটি বিদ্যমান নয়।

```jsx
server.listen(3020);
console.log("Server Run Success");
```

- **`server.listen(3020);`**: সার্ভারটি 3020 পোর্টে শোনার জন্য প্রস্তুত হয়।
- **`console.log("Server Run Success");`**: সার্ভারটি সফলভাবে চালু হলে এটি কনসোলে একটি বার্তা প্রদর্শন করে।

### গুরুত্বপূর্ণ নোট:

- **`fs.exists`** মেথডটি ভবিষ্যতে ব্যবহার থেকে বাদ দেওয়া হতে পারে, তাই এটি ব্যবহার করা সঠিক নয়। এর পরিবর্তে `fs.access` ব্যবহার করা ভাল।
- সার্ভারটি চালু করার পর, আপনি একটি ব্রাউজার বা HTTP ক্লায়েন্টের মাধ্যমে `http://localhost:3020` URL এ গিয়ে ফাইলের অস্তিত্ব পরীক্ষা করতে পারেন।

# **FS File Exists Sync**

```jsx
const fs = require('fs');
const http = require('http');

const server = http.createServer((req,res) => {
    //Sync
    if(req.url==="/"){
        
        let error = fs.existsSync('newDemo.txt');

            if (error) {
                res.end(` File Exist`);
            } else {
                res.end(`File Does not exist`);
            }
    }
});

// OutPut :- File Exist

server.listen(3030);
console.log("Server Run Success"); 
```

এই কোডটি একটি HTTP সার্ভার তৈরি করে যা একটি নির্দিষ্ট URL ("/") এ একটি ফাইলের অস্তিত্ব পরীক্ষা করে। নিচে কোডের প্রতিটি অংশের বাংলা ব্যাখ্যা দেওয়া হল:

```jsx
const fs = require('fs');
const http = require('http');

```

- **`const fs = require('fs');`**: এটি Node.js এর ফাইল সিস্টেম মডিউল `fs` কে অন্তর্ভুক্ত করে, যা ফাইল এবং ডিরেক্টরি ম্যানিপুলেশনের জন্য ব্যবহৃত হয়।
- **`const http = require('http');`**: এটি Node.js এর HTTP মডিউলকে অন্তর্ভুক্ত করে, যা HTTP সার্ভার তৈরি করতে ব্যবহৃত হয়।

```jsx
const server = http.createServer((req, res) => {
```

- **`const server = http.createServer(...);`**: এটি একটি HTTP সার্ভার তৈরি করে। সার্ভারটি `req` (অনুরোধ) এবং `res` (প্রতিক্রিয়া) নামক দুটি প্যারামিটার গ্রহণ করে।

```jsx
    if (req.url === "/") {
```

- **`if (req.url === "/") {`**: এই শর্তটি পরীক্ষা করে যে ব্যবহারকারীর অনুরোধের URL টি "/" কিনা। যদি তাই হয়, তাহলে নিচের কোড ব্লকটি কার্যকর হবে।

```jsx
        let error = fs.existsSync('newDemo.txt');
```

- **`let error = fs.existsSync('newDemo.txt');`**: এই লাইনটি `newDemo.txt` নামের ফাইলটির অস্তিত্ব পরীক্ষা করে সিঙ্ক্রোনাসভাবে। `fs.existsSync` মেথডটি যদি ফাইলটি বিদ্যমান হয়, তাহলে `error` ভেরিয়েবলে `true` মান রাখা হবে; অন্যথায়, `false` হবে।

```jsx
            if (error) {
                res.end(` File Exist`);
            } else {
                res.end(`File Does not exist`);
            }
```

- **`if (error) { ... }`**: যদি `error` ভেরিয়েবলটি `true` হয় (অর্থাৎ, ফাইলটি বিদ্যমান), তাহলে এই ব্লকটি কার্যকর হবে।
    - **`res.end(` File Exist`);`**: এটি সার্ভার থেকে ক্লায়েন্টকে জানায় যে ফাইলটি বিদ্যমান।
- **`else { ... }`**: যদি `error` ভেরিয়েবলটি `false` হয় (অর্থাৎ, ফাইলটি বিদ্যমান নয়), তাহলে এই ব্লকটি কার্যকর হবে।
    - **`res.end(`File Does not exist`);`**: এটি সার্ভার থেকে ক্লায়েন্টকে জানায় যে ফাইলটি বিদ্যমান নয়।

```jsx
server.listen(3030);
console.log("Server Run Success");
```

- **`server.listen(3030);`**: সার্ভারটি 3030 পোর্টে শোনার জন্য প্রস্তুত হয়।
- **`console.log("Server Run Success");`**: সার্ভারটি সফলভাবে চালু হলে এটি কনসোলে একটি বার্তা প্রদর্শন করে।

### সারসংক্ষেপ:

এই কোডটি একটি HTTP সার্ভার তৈরি করে যা একটি নির্দিষ্ট URL ("/") এ ফাইলের অস্তিত্ব পরীক্ষা করে এবং ফলস্বরূপ একটি বার্তা ক্লায়েন্টকে পাঠায়, যা বলে যে ফাইলটি বিদ্যমান কিনা। আপনি যখন সার্ভারটি চালু করবেন এবং একটি ব্রাউজার বা HTTP ক্লায়েন্টের মাধ্যমে `http://localhost:3030` URL এ প্রবেশ করবেন, তখন সার্ভার ফাইলটির অস্তিত্বের ভিত্তিতে উপযুক্ত বার্তা প্রদান করবে।