# 🗄️ Data and Databases Basics

## 📖 What is Data?

**Data** is information that a computer can store, process, organize,
or transmit.

I interact with data every day, even when I may not realize it.

Examples of data include:

- 👤 Names
- 📧 Email addresses
- 📱 Phone numbers
- 💰 Prices
- 📅 Dates
- 🖼️ Pictures
- 🎵 Music
- 🎥 Videos
- 📍 Locations
- 🎮 Game statistics

Computers can use data to help applications perform useful tasks.

---

## 🖼️ What Do Data and Databases Look Like?

![Example of data stored in a database](database-example.jpg)

Data can be organized in many different ways.

A database may organize information into structures containing things
such as:

- Rows
- Columns
- Records
- Fields

This can make large amounts of information easier to store, search,
update, and manage.

---

## 💡 Simple Example

Imagine I have information about students in a class.

I could write everything randomly on pieces of paper.

That would quickly become difficult to organize.

Instead, I could create something like this:

| Student ID | Name | Major |
|---|---|---|
| 001 | Jordan | Cybersecurity |
| 002 | Taylor | Computer Science |
| 003 | Morgan | Networking |

Now the information has structure.

It becomes easier to answer questions such as:

> What is Jordan's major?

or:

> Which students are studying cybersecurity?

Databases use organized structures to make working with information
easier.

---

# 🗄️ What is a Database?

A **database** is an organized collection of data.

Databases allow information to be stored in a way that makes it easier
to:

- ➕ Add information
- 🔎 Search for information
- ✏️ Update information
- 🗑️ Remove information
- 📊 Analyze information

Databases are used by many of the applications and services people use
every day.

---

## 🌎 Real-World Example

Imagine I create an account on a shopping website.

The company may need to store information associated with my account.

This could include:

- My name
- My account information
- My orders
- My shopping cart
- My shipping information

Instead of keeping this information in random files, the company can use
databases to organize it.

When I log back into the website, the application can retrieve
information associated with my account.

---

# 📊 Tables

One common way of organizing information in some databases is with
**tables**.

A table can organize information using:

**Columns**

and

**Rows**

It may look similar to a spreadsheet.

Example:

| Product ID | Product | Price |
|---|---|---:|
| 101 | Keyboard | $30 |
| 102 | Mouse | $20 |
| 103 | Monitor | $150 |

---

# ↔️ Rows

A **row** can represent one individual record.

For example:

| Product ID | Product | Price |
|---|---|---:|
| 101 | Keyboard | $30 |

This row contains information about one product.

A row is also commonly called a:

**Record**

---

# ↕️ Columns

A **column** represents a category or type of information.

For example:

**Product**

is one column.

**Price**

is another column.

Columns help keep similar types of information organized.

---

# 📝 Fields

A **field** stores an individual piece of data within a record.

For example:

If a student record contains:

**Name:** Jordan

then:

`Jordan`

is the value stored in the Name field.

At this beginner level, I can think about it like this:

> 📊 Table = collection of organized information

> ↔️ Row = one record

> ↕️ Column = one category

> 📝 Field = individual piece of information

---

# 🔑 Unique Identifiers

Databases often need a way to tell records apart.

Imagine two customers are both named:

**John Smith**

Using only the name could cause confusion.

Instead, a system might assign each customer a unique ID.

For example:

`Customer ID: 10234`

Another customer might have:

`Customer ID: 10789`

Even if they have the same name, their IDs are different.

---

# 🏥 Where Are Databases Used?

Databases are used in many industries.

### 🏥 Healthcare

Databases can help manage information such as:

- Patient records
- Appointments
- Medications
- Billing information

### 🏦 Banking

Databases can help manage:

- Accounts
- Transactions
- Customer information

### 🏫 Schools

Databases can store:

- Student information
- Classes
- Grades
- Enrollment information

### 🛒 Stores

Databases can manage:

- Products
- Inventory
- Customers
- Orders

### 🎮 Video Games

Games can use databases to store information such as:

- Player accounts
- Rankings
- Statistics
- Inventory
- Progress

---

# 🔍 What is a Query?

A **query** is a request for information from a database.

Imagine a database containing thousands of products.

Instead of manually looking through every product, I might want to ask:

> Show me products that cost less than $50.

A database system can search its data and return matching information.

That request is an example of a query.

---

# 💬 What is SQL?

**SQL** stands for:

**Structured Query Language**

SQL is commonly used to work with relational databases.

It can be used to perform tasks such as:

- 🔎 Retrieving data
- ➕ Adding data
- ✏️ Updating data
- 🗑️ Removing data

At this beginner level, I do **not** need to memorize SQL commands yet.

For now, the important idea is:

> 💡 SQL is a language that can be used to communicate with certain
> databases.

---

# 🧹 Why Does Data Need to Be Organized?

Poorly organized data can create problems.

For example, imagine a customer appears in a system as:

`KaVonne Wright`

Then another record says:

`Kavonne Wright`

Then another says:

`K. Wright`

A computer may not automatically know whether these records represent
the same person.

Keeping data organized and consistent can make information easier to
use and analyze.

---

# 🔐 Databases and Cybersecurity

Databases can contain sensitive information.

Examples include:

- 🔑 Account information
- 💳 Financial information
- 🏥 Medical information
- 👤 Personal information
- 📧 Email addresses

Because databases can contain valuable information, organizations need
to protect them.

Security protections can include:

- 🔐 Access controls
- 🔑 Authentication
- 🔒 Encryption
- 💾 Backups
- 🔄 Updates

This connects directly to the cybersecurity concepts from Lesson 9.

---

## 🛠️ Why Does This Matter in IT?

Someone working in IT may interact with systems that depend on
databases.

Understanding basic database concepts can help me understand:

- 📊 How information is organized
- 🔎 How applications retrieve information
- 👤 How user records are stored
- 🔐 Why data needs protection
- 💾 Why databases need backups
- 🛠️ How business applications work

I do not need to become a database administrator to benefit from
understanding the basics.

---

# 🧪 Beginner Activity: Build a Simple Data Table

For this activity, I will create a small example of structured data.

I can use:

- Microsoft Excel
- Google Sheets
- Another spreadsheet program

The purpose is not to create a real database.

The goal is to understand how information can be organized into rows
and columns.

---

## 🖥️ Step 1: Open a Spreadsheet

I will open a blank spreadsheet.

---

## 📝 Step 2: Create My Columns

I will create these column headings:

| Device ID | Device Type | Operating System | Location |
|---|---|---|---|

---

## 💻 Step 3: Add Example Devices

I will add at least five example devices.

For example:

| Device ID | Device Type | Operating System | Location |
|---|---|---|---|
| 001 | Laptop | Windows | Classroom |
| 002 | Desktop | Linux | Computer Lab |
| 003 | Smartphone | Android | Office |

I will create the remaining examples myself.

---

## 🔎 Step 4: Examine My Data

I will identify:

**One row**

**One column**

**One field**

**One unique Device ID**

This will help me connect the terminology to information I can actually
see.

---

# 📸 My Data Activity

After completing the activity, I can add my screenshot here.

![My beginner data table](my-data-table.png)

> 🔒 I will only use fictional/example information for this activity.
> I should not place real personal, medical, financial, or other
> sensitive information in my public GitHub repository.

---

# 📝 My Results

**Number of records I created:**  
`Add my result here`

**One column I identified:**  
`Add my result here`

**One field I identified:**  
`Add my result here`

**One unique ID I created:**  
`Add my result here`

### 👀 What I Observed

`I will describe what I personally noticed while organizing the data.`

---

# 🧠 Quick Knowledge Check

### 1. What is data?

`My answer:`

### 2. What is a database?

`My answer:`

### 3. What does a row usually represent?

`My answer:`

### 4. What does a column represent?

`My answer:`

### 5. Why can unique IDs be useful?

`My answer:`

### 6. What is a database query?

`My answer:`

### 7. What does SQL stand for?

`My answer:`

### 8. Why should databases be protected?

`My answer:`

---

# 🔗 Connecting This to Previous Lessons

The concepts from the previous lessons can now be connected to data.

### 💾 Storage

Data needs somewhere to be stored.

### 🪟 Operating Systems

Operating systems help applications access and manage stored
information.

### 📦 Applications

Applications can create, retrieve, update, and display data.

### 🌐 Networks

Data can travel between computers across networks.

### 🔐 Cybersecurity

Sensitive data needs to be protected from unauthorized access,
modification, loss, and theft.

### 🗄️ Databases

Databases provide organized ways to store and manage information.

---

# 🎓 What I Learned

I learned that data is information that computers can store, process,
organize, and transmit.

I learned that databases are organized collections of data.

I also learned basic terms including tables, rows, columns, records,
fields, unique identifiers, and queries.

I was introduced to SQL and learned that it is a language commonly used
to work with relational databases.

I also learned that databases are used in many real-world industries
and may contain sensitive information that needs to be protected.

Finally, I practiced organizing example information into a structured
table.

---

## 📚 About This Lesson

**Course:** CSIS 110  
**Topic:** Data and Databases  
**Level:** 🌱 Beginner  
**Status:** 🟡 Learning

> 💡 These notes are written from a beginner's perspective. My goal is
> to document what I am learning while explaining the concepts in a way
> that can also help other students who are new to computers and IT.
