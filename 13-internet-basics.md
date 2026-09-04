# 🌐 Internet Basics

The Internet is something I use almost every day, but before this lesson I may not have thought much about what is actually happening behind the scenes.

When I open a website, watch a video, play an online game, send an email, or use an online application, multiple computers, networks, and services work together to make that possible.

In this lesson, I am learning the basic concepts behind the Internet, how devices communicate, and what happens when I visit a website.

---

## 📖 What Is the Internet?

The **Internet** is a worldwide collection of connected computer networks.

It allows computers, phones, servers, gaming consoles, smart devices, and many other devices to communicate with each other.

A simple way to think about it is:

> 💡 **The Internet is a giant network made up of many smaller networks connected together.**

The Internet itself is not one computer, one company, or one building.

It is made up of networks and devices located around the world.

---

## 🖼️ What Does the Internet Look Like?

![Internet Basics](internet-basics.jpg)

The Internet does not exist only in the air.

It depends on physical technology such as:

- 🖥️ Computers
- 🌐 Routers
- 📡 Wireless access points
- 🗄️ Servers
- 🔌 Network cables
- 🌊 Undersea fiber-optic cables
- 🏢 Data centers
- 📱 Phones and other connected devices

When I connect to the Internet, my device becomes part of a much larger system of connected networks.

---

# 💡 A Simple Internet Analogy

I can think of the Internet like a giant system of roads.

🚗 **Data** = Cars traveling on the roads

🛣️ **Networks** = Roads

🌐 **Routers** = Intersections directing traffic

🏠 **IP addresses** = Street addresses

📖 **DNS** = A directory that helps find addresses

🏢 **Servers** = Destinations containing information

Just like a package needs an address to reach the correct house, information traveling across networks needs addressing information to reach the correct device.

---

# 🌐 Internet vs. World Wide Web

The **Internet** and the **World Wide Web** are related, but they are not exactly the same thing.

### 🌐 Internet

The Internet is the network infrastructure that allows devices around the world to communicate.

### 🌍 World Wide Web

The **World Wide Web**, often called the **Web**, is a collection of websites and webpages that people access using the Internet.

A simple way to remember this is:

> 🌐 **The Internet is the network.**
>
> 🌍 **The Web is one service that uses the Internet.**

Other services can also use the Internet, including:

- Email
- Online gaming
- Video calls
- File transfers
- Cloud services
- Messaging applications

---

# 🏢 What Is an ISP?

**ISP** stands for **Internet Service Provider**.

An ISP is a company or organization that provides Internet access.

A home network usually connects to an ISP, and the ISP helps connect that network to the larger Internet.

A simplified connection might look like:

**My Computer → Home Network → ISP → Internet → Destination**

Without some type of Internet connection, my home network could still allow devices inside the home to communicate, but it would not necessarily have access to the larger Internet.

---

# 📡 Modems and Routers

Modems and routers are commonly used when connecting devices to the Internet.

Although people sometimes use the words interchangeably, they perform different jobs.

## 📡 Modem

A **modem** helps connect a home or business network to an Internet service.

It communicates with the Internet service provided by the ISP.

## 🌐 Router

A **router** helps direct network traffic between devices and networks.

At home, a router can allow multiple devices to share an Internet connection.

For example:

**Internet**
↓
**Modem**
↓
**Router**
↓
**Laptop • Phone • TV • Game Console**

Some Internet equipment combines modem and router functions into one device.

---

# 🏠 What Is an IP Address?

An **IP address** is an address used to identify a device or network interface on an IP network.

IP stands for:

**Internet Protocol**

Devices use IP addresses to help information reach the correct destination.

A simple analogy is a mailing address.

If someone wants to send a package to me, they need to know where to send it.

Computers also need addressing information when communicating across networks.

---

## 🔢 IPv4 Example

An IPv4 address may look similar to:

`192.168.1.10`

IPv4 addresses contain four groups of numbers separated by periods.

---

## 🔢 IPv6 Example

An IPv6 address may look similar to:

`2001:db8:1234:5678::1`

IPv6 was developed partly because the number of Internet-connected devices grew beyond what the original IPv4 address space could comfortably support.

> 💡 **Beginner Tip:** I do not need to memorize every detail of IP addressing yet. The important idea is that IP addresses help devices identify and communicate with destinations on networks.

---

# 📖 What Is DNS?

**DNS** stands for:

**Domain Name System**

DNS helps computers translate human-friendly domain names into information they can use to locate Internet resources.

Humans are usually better at remembering:

`example.com`

than remembering an IP address.

DNS helps connect those two ideas.

A simple way to think about DNS is:

> 📖 **DNS is similar to a contact list for the Internet.**

I know the name I want.

DNS helps my computer find where it needs to go.

---

# 🔗 What Is a URL?

**URL** stands for:

**Uniform Resource Locator**

A URL identifies the location of a resource on the Web.

For example:

`https://www.example.com`

A URL can contain several pieces of information.

### Example

`https://www.example.com/page`

**https** → protocol/scheme

**example.com** → domain name

**/page** → path to a particular resource

URLs help browsers determine what resource I want to access.

---

# 🧭 What Is a Web Browser?

A **web browser** is software used to access and display content from the World Wide Web.

Examples of browsers include:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Apple Safari

When I enter a website address into a browser, the browser communicates with other systems over a network to request the information needed to display the webpage.

---

# 🗄️ What Is a Server?

A **server** is a computer or computer system that provides resources or services to other computers.

The device requesting those resources is often called a **client**.

For example:

🧑‍💻 **My Computer = Client**

🌐 **Website's Computer = Server**

My computer requests information.

The server responds with information.

This relationship is called the:

**Client-Server Model**

---

# ⚙️ What Happens When I Visit a Website?

When I type a website address into my browser, several things can happen very quickly.

A simplified version looks like this:

### 1️⃣ I enter a URL

I type a website address into my browser.

↓

### 2️⃣ DNS helps locate the destination

My device needs information about where the website can be reached.

↓

### 3️⃣ My request travels across networks

Routers and other network equipment help move the traffic toward its destination.

↓

### 4️⃣ The server receives the request

The website's server receives my request.

↓

### 5️⃣ The server responds

The server sends information back toward my device.

↓

### 6️⃣ My browser displays the webpage

My browser processes the information and displays the page.

All of this can happen in a very short amount of time.

---

# 🔐 HTTP vs. HTTPS

When browsing the Web, I may see:

`http://`

or

`https://`

### 🌐 HTTP

**HTTP** stands for:

**Hypertext Transfer Protocol**

It is used for communication between web clients and web servers.

### 🔒 HTTPS

**HTTPS** is the secure version of HTTP.

The **S** stands for **Secure**.

HTTPS uses encryption to help protect information while it travels between my browser and the website.

> 🔐 **Important:** HTTPS helps protect the connection, but it does not automatically mean that every website using HTTPS is trustworthy.

A malicious website can still use HTTPS.

---

# 📥 Downloading vs. 📤 Uploading

These two terms describe the direction information is moving.

## 📥 Download

A **download** moves data from another system to my device.

Examples:

- Downloading a game
- Saving a picture
- Downloading a document

## 📤 Upload

An **upload** moves data from my device to another system.

Examples:

- Uploading a picture
- Submitting an assignment
- Uploading a video
- Adding a file to GitHub

A simple way to remember it:

> 📥 **Download = Data comes to me**
>
> 📤 **Upload = Data goes from me**

---

# 🚀 Bandwidth

**Bandwidth** describes how much data a network connection can carry during a certain amount of time.

Higher bandwidth can allow more data to move across a connection.

For example, activities such as:

- Streaming high-quality video
- Downloading large games
- Video calling
- Transferring large files

can use significant bandwidth.

Bandwidth is commonly measured using units such as:

**Mbps — Megabits per second**

or

**Gbps — Gigabits per second**

---

# ⏱️ Latency

**Latency** describes the delay involved in data traveling between locations.

Low latency means there is less delay.

High latency means there is more delay.

This can be especially noticeable during:

🎮 Online gaming

📞 Video calls

🎙️ Voice chat

For example, I could have a fast Internet connection but still experience noticeable delay if latency is high.

> 💡 **Bandwidth and latency are different.**
>
> Bandwidth is about how much data can move.
>
> Latency is about how long communication takes.

---

# 🔌 Wired vs. 📶 Wireless Internet Connections

Devices can connect to networks in different ways.

## 🔌 Wired

A wired network connection commonly uses an **Ethernet cable**.

Possible advantages include:

- Stable connection
- Consistent performance
- Lower interference

## 📶 Wireless

Wi-Fi allows devices to connect without an Ethernet cable.

Possible advantages include:

- Mobility
- Convenience
- Fewer cables

However, wireless performance can be affected by things such as distance, walls, interference, and network congestion.

---

# ☁️ Internet Services

The Internet supports many services that I use regularly.

Examples include:

📧 Email

🎮 Online gaming

🎥 Video streaming

☁️ Cloud storage

💬 Messaging

📞 Video calling

🛒 Online shopping

🏦 Online banking

🎓 Online education

These services depend on networks and computer systems communicating with each other.

---

# 🔐 Internet Safety

Connecting to the Internet creates many opportunities, but it also creates security risks.

Some common Internet threats include:

🎣 Phishing

🦠 Malware

🔑 Stolen passwords

🌐 Fake websites

👤 Identity theft

📨 Scam messages

🔓 Unsecured accounts

Some basic security practices include:

- Using strong passwords
- Using different passwords for important accounts
- Enabling multi-factor authentication when available
- Keeping software updated
- Being careful with unexpected links and attachments
- Checking website addresses
- Avoiding sharing sensitive information unnecessarily

---

# 🛠️ Why Internet Knowledge Matters in IT

Understanding how the Internet works is important for IT professionals.

If someone says:

> "My Internet isn't working."

An IT professional needs to determine where the problem might be.

The issue could involve:

- The computer
- Wi-Fi
- Ethernet
- Router
- Modem
- DNS
- ISP
- Website
- Network configuration

Understanding the basic pieces makes troubleshooting easier.

---

# 🧪 Beginner Activity — Investigate My Internet Connection

For this activity, I will look at some basic information about my own Internet connection.

I will use Windows for this activity.

> ⚠️ **Privacy Reminder:** I should review screenshots before uploading them to GitHub and make sure I am comfortable sharing the information shown.

---

## Step 1 — Open Command Prompt

1. Click the **Start** button.
2. Type:

`Command Prompt`

3. Click **Command Prompt**.

A black window should appear.

This is called the **Command Prompt**.

---

## Step 2 — View My Network Information

Type:

`ipconfig`

Then press **Enter**.

Windows will display information about my network connections.

I may see information such as:

- IPv4 Address
- Subnet Mask
- Default Gateway

> 💡 I do not need to understand every line yet.

For this activity, I am simply becoming familiar with what network information looks like.

---

## Step 3 — Find the Default Gateway

Look for:

`Default Gateway`

The default gateway is commonly the router that my device uses to reach destinations outside the local network.

I should recognize that this address belongs to part of my network configuration.

---

## Step 4 — Test Network Communication

In Command Prompt, type:

`ping example.com`

Then press **Enter**.

The **ping** command can help test whether my computer can communicate with another system over a network.

I may see:

- Replies
- Response times
- Packet information

---

## Step 5 — Look at the Response Time

Look for a value measured in:

`ms`

This means **milliseconds**.

The response time gives me a basic example of network delay.

This connects to the concept of **latency**.

---

# 📸 My Activity Screenshot

After completing the activity, I can take a screenshot of my Command Prompt.

Before uploading it to GitHub, I should check the screenshot for information I do not want to share publicly.

![My Internet Activity](my-internet-activity.png)

---

# 📝 My Results / What I Observed

**Connection type (Wi-Fi or Ethernet):**

**Did `ipconfig` display an IPv4 address?**

**Did I find a Default Gateway?**

**Did the ping test receive replies?**

**Approximate response time:**

**Something I noticed:**

**Something I did not understand yet:**

**Something new I learned:**

---

# 🧠 Quick Knowledge Check

### 1. What is the Internet?

**Answer:**

---

### 2. What is the difference between the Internet and the World Wide Web?

**Answer:**

---

### 3. What does ISP stand for?

**Answer:**

---

### 4. What is the basic purpose of an IP address?

**Answer:**

---

### 5. What does DNS do?

**Answer:**

---

### 6. What is the difference between uploading and downloading?

**Answer:**

---

### 7. What is the difference between bandwidth and latency?

**Answer:**

---

### 8. Why is HTTPS generally safer than HTTP?

**Answer:**

---

### 9. What is the difference between a client and a server?

**Answer:**

---

### 10. What does the `ping` command help test?

**Answer:**

---

# 🔗 Connection to Previous Lessons

The Internet connects to many concepts I have already learned in CSIS 110.

🧠 **RAM** temporarily holds information that applications are actively using.

⚙️ **CPU** processes instructions involved in running browsers and network applications.

💾 **Storage** holds downloaded files, applications, and other data.

⌨️🖥️ **Input and Output Devices** allow me to interact with websites and Internet applications.

🧩 **Motherboards** connect computer components, including network hardware.

🪟 **Operating Systems** manage network connections and allow applications to communicate.

📦 **Software and Applications** use Internet connections to provide services.

🌐 **Networking Basics** explain how devices communicate and connect to other networks.

🔐 **Cybersecurity** helps protect Internet-connected devices, accounts, and information.

🗄️ **Data and Databases** store information used by websites and online services.

💻 **Programming** is used to build websites, applications, servers, and Internet services.

🤖 **Emerging Technologies** often depend on Internet connectivity, cloud systems, and large amounts of data.

The Internet brings many of these technologies together.

---

# 🎓 What I Learned

From this lesson, I learned that the Internet is much more than websites.

It is a worldwide collection of connected networks that allows devices and computer systems to communicate.

I learned the basic purpose of:

- ISPs
- Modems
- Routers
- IP addresses
- DNS
- URLs
- Browsers
- Servers
- HTTP and HTTPS

I also learned the difference between:

- Internet and World Wide Web
- Uploading and downloading
- Bandwidth and latency
- Wired and wireless connections
- Clients and servers

The hands-on activity also introduced me to basic Windows networking commands such as `ipconfig` and `ping`.

Understanding these concepts gives me a better foundation for learning networking, troubleshooting, and cybersecurity.

---

# 📚 About This Lesson

**Course:** CSIS 110 – Introduction to Computer Science  
**Topic:** Internet Basics  
**Level:** 🌱 Beginner  
**Status:** 🟡 Learning

---

> 💡 **These notes are written from a beginner's perspective. My goal is to document what I am learning while explaining the concepts in a way that can also help other students who are new to computers and IT.**
