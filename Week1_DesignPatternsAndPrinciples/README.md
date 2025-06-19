# 🧠 Week 1 Notes – Design Patterns & Principles (DN 4.0 – .NET FSE)

Hey there 👋 — this is my Week 1 brain dump!  
This folder covers all the major stuff like SOLID principles and 11 design patterns.  
I'm going to keep it simple, visual, and beginner-friendly 💡

---

## 🌱 What are Design Principles?

🧭 Think of design principles as **rules for writing good code**.  
They help make code:

✅ Understandable  
✅ Maintainable  
✅ Extendable  
✅ Less buggy

---

## 🔐 SOLID Principles – The Core 5

| Principle | Meaning | Memory Tip 🧠 |
|----------|--------|---------------|
| **S** – Single Responsibility | One class = One job | “Don’t multitask!” |
| **O** – Open/Closed | Open for extension, closed for modification | “Plug it in, don’t break it” |
| **L** – Liskov Substitution | Subclass should work like the parent | “Child should act like parent” |
| **I** – Interface Segregation | Don’t force unwanted methods | “No extra baggage” |
| **D** – Dependency Inversion | Depend on interfaces, not concrete | “Talk to abstractions” |


---

## 🧱 What are Design Patterns?

🎯 Design patterns are **like cheat codes** in coding.  
They're reusable solutions to common problems.

🛠️ You don't copy-paste them — you apply the **idea** in your way.

---

## 🏗️ Types of Design Patterns

### 1️⃣ Creational Patterns – “How to create objects”

| Pattern     | Purpose | Think of... |
|-------------|---------|-------------|
| **Singleton** | Only 1 instance | Government ID system |
| **Factory** | Decide object type at runtime | Pizza maker chooses your pizza |
| **Builder** | Build complex object step-by-step | Ordering a custom burger |

---

### 2️⃣ Structural Patterns – “How to structure objects together”

| Pattern     | Purpose | Think of... |
|-------------|---------|-------------|
| **Adapter** | Convert one format to another | Charging your phone with different plugs |
| **Decorator** | Add features on top | Adding toppings to your ice cream |
| **Proxy** | Act as a gatekeeper | Netflix profile → asks if you're allowed first |

---

### 3️⃣ Behavioral Patterns – “How objects communicate”

| Pattern     | Purpose | Think of... |
|-------------|---------|-------------|
| **Observer** | Notify others of changes | YouTube notifications |
| **Strategy** | Choose logic at runtime | Google Maps switching routes |
| **Command** | Wrap a request as an object | Smart remote controlling devices |

---

### 4️⃣ Architectural Extras – Big picture stuff

| Pattern        | What it does | Where? |
|----------------|--------------|--------|
| **MVC**        | Splits logic, data, and view | ASP.NET MVC |
| **Dependency Injection (DI)** | Inject instead of creating objects | ASP.NET Core services |

---

## 📘 Here's What I’ll Be Doing This Week:

| #  | Pattern / Principle         | Folder Name              |
|----|-----------------------------|--------------------------|
| 01 | Singleton                   | `01_Singleton`           |
| 02 | Factory Method              | `02_Factory`             |
| 03 | Builder                     | `03_Builder`             |
| 04 | Adapter                     | `04_Adapter`             |
| 05 | Decorator                   | `05_Decorator`           |
| 06 | Proxy                       | `06_Proxy`               |
| 07 | Observer                    | `07_Observer`            |
| 08 | Strategy                    | `08_Strategy`            |
| 09 | Command                     | `09_Command`             |
| 10 | MVC                         | `10_MVC`                 |
| 11 | Dependency Injection (DI)  | `11_DependencyInjection` |

---

## 💡 Real Life Analogy Map

ingleton 🔒 – One boss in a company
Factory 🍕 – Order pizza, get different types
Builder 🍔 – Custom burger with addons
Adapter 🔌 – USB-to-C plug
Decorator 🧁 – Sprinkles on a cupcake
Proxy 🪪 – Doorman checking ID
Observer 📣 – You get notified on Insta
Strategy 🗺️ – Choose best travel route
Command 🎮 – Remote control sends commands
MVC 🧠👁️🛠️ – Brain, Eye, Hand
DI 🧃 – Juice comes in, not made inside


---

## 🧪 Goal This Week

- ✅ Understand each pattern 💭
- ✅ Write C# code for each 🧑‍💻
- ✅ Save screenshot outputs 📸
- ✅ Push everything to GitHub 📤

Let’s gooo! 🚀

