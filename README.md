# Cloudflare Internship Application: Systems

## Problem statement?

Please write a small Ping CLI application for MacOS or Linux.
The CLI app should accept a hostname or an IP address as its argument, then send ICMP "echo requests" in a loop to the target while receiving "echo reply" messages.
It should report loss and RTT times for each sent message.

Please choose from among these languages: C/C++/Go/Rust

## Requirements

### 1. Use one of the specified languages

Please choose from among C/C++/Go/Rust. If you aren't familiar with these languages, you're not alone! Many engineers join Cloudflare without
specific langauge experience. Please consult [A Tour of Go](https://tour.golang.org/welcome/1) or [The Rust Programming Language](https://doc.rust-lang.org/book/index.html).

### 2. Build a tool with a CLI interface

The tool should accept as a positional terminal argument a hostname or IP address.

### 3. Send ICMP "echo requests" in an infinite loop

As long as the program is running it should continue to emit requests with a periodic delay.

### 4. Report loss and RTT times for each message

Packet loss and latency should be reported as each message received.

## How to use

### 1. Clone repo

### 2. Run makefile

### 3. Execute 
#### `$sudo ./ping ipv4addr` 
#### `$sudo ./ping hostname`

### 4. To exit
#### hold `Ctrl` and `c` to interrupt 
