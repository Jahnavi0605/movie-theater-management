# 🎬 Movie Theater Management System (SMTMS)

**Language:** Python | **UI:** tkinter | **Database:** SQLite

## Overview
A full-featured desktop application for managing a movie theater — built entirely in Python with a tkinter GUI and SQLite backend. The system supports three distinct user roles, a complete ticket booking flow, and admin reporting with PDF export.

## ✨ Features

### 👤 Three User Roles
| Role | Capabilities |
|---|---|
| **Admin** | Add/remove movies, change prices, manage salespersons, view all reports |
| **Salesperson** | Search movies, book tickets for customers |
| **Customer** | Browse movies (Trending, Upcoming, All), book seats, view bookings |

### 🎥 Core Functionality
- **Movie browsing** — Top Trending, Upcoming, and All Movies views
- **Seat booking** — Select show date, time, and number of seats
- **User authentication** — Login, sign-up, and password reset
- **Movie reports** — Per-film performance data
- **Booking reports** — Full booking history with dates, titles, and ticket counts
- **User reports** — Admin view of all registered users
- **PDF export** — Print any report as a PDF

## 🛠️ Tech Stack
- **Language:** Python 3
- **GUI:** tkinter, ttk
- **Database:** SQLite3 (3 separate databases)
- **Libraries:** os, sys, filedialog, messagebox

## 🗄️ Database Schema

### users.db
```sql
