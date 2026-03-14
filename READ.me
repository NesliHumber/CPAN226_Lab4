# CPAN226 Lab 4 – Multithreading and Network Concurrency

Neslihan Ustaoglu - n01734911
Course: CPAN226
Semester: Winter 2026

---

# Project Overview

This lab demonstrates the performance difference between a **sequential server** and a **multithreaded server** when handling multiple client requests.

The sequential server processes client connections **one at a time**, creating a performance bottleneck.
The multithreaded server uses the **pthread library** so that each client request can be handled **concurrently** in a separate thread.

The goal of this lab is to measure how multithreading reduces total execution time in network applications.

---

# Project Structure

```
CPAN226_Lab4
│
├── client
│   └── client.c
│
├── server
│   ├── timedDelayNothreads.c
│   └── timedDelayThreads.c
│
├── README.md

```

### server/

Contains the server implementations.

* **timedDelayNothreads.c**
  Sequential server that processes one client at a time.

* **timedDelayThreads.c**
  Multithreaded server implementation using pthreads.

### client/

Contains the client program used to simulate multiple requests to the server.

---

# Requirements

Before running the project, ensure the following tools are installed:

* MinGW (GCC) or Clang compiler
* pthread library
* A Unix-based terminal (macOS or Linux) or Windows with MinGW

To verify the compiler installation:

```
gcc --version
```

or

```
clang --version
```

---

# Compilation Instructions

Open a terminal in the root project folder.

## Compile the Sequential Server

```
clang server/timedDelayNothreads.c -o timedDelayNothreads
```

or

```
gcc server/timedDelayNothreads.c -o timedDelayNothreads
```

---

## Compile the Multithreaded Server

```
clang server/timedDelayThreads.c -o timedDelayThreads -lpthread
```

or

```
gcc server/timedDelayThreads.c -o timedDelayThreads -lpthread
```

---

## Compile the Client Program

```
clang client/client.c -o client -lpthread
```

or

```
gcc client/client.c -o client -lpthread
```

---

# Running the Program

Testing requires **two terminal windows**.

---

## Terminal 1 – Start the Server

Run either the sequential server or the multithreaded server.

Sequential version:

``` ON PowerShell
.\timedDelayNothreads.exe
```
``` ON Command Prompt
timedDelayNothreads.exe
```

Multithreaded version:

``` ON PowerShell
.\timedDelayThreads.exe
```
``` ON Command Prompt
timedDelayThreads.exe
```

The server will start listening on **port 8080**.

---

## Terminal 2 – Run the Client

``` ON PowerShell
.\client.exe
```
``` ON Command Prompt
client.exe
```

The client will create multiple parallel requests to the server.

---

# Expected Results

### Sequential Server

Each request waits for the previous one to finish.

Expected total time:

```
~25 seconds
```

This occurs because each request includes a **5 second delay** and the server processes requests one-by-one.

---

### Multithreaded Server

Each request runs in its own thread.

Expected total time:

```
~5 seconds
```

The requests run concurrently, so the delays overlap instead of stacking.

---

# Key Concepts Demonstrated

* Multithreading using the **pthread library**
* Network communication using **TCP sockets**
* Performance improvements through **concurrency**
* Handling multiple clients simultaneously

---
