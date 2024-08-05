# WhatsApp-like Contact Management and Chat Application

## Overview
This project is a C++ application that simulates a WhatsApp-like contact management and chat system. It provides a platform to create accounts, manage contacts, and chat with other users. The application leverages data structures such as linked lists, hash tables, and stacks to efficiently handle contacts and chat history.

## Features
- **Account Management:** Create new accounts and log in with existing credentials.
- **Contact Management:** Add, delete, update, and search for contacts with ease.
- **Chat System:** Engage in conversations with contacts, view recent chats, and save chat history.
- **Data Storage:** Persist contacts and chat history to text files for easy retrieval.

## File Structure
- `whatsapp_list.cpp`: Contains the main application logic and user interface.
- `Hashtable.h`: Implements a hash table for efficient contact searching.
- `SinglyList.h`: Defines a singly linked list for managing contacts.
- `stack.h`: Provides a stack for managing recent chats.

## Getting Started

### Compilation
To compile the code, use the following command:
```bash
g++ whatsapp_list.cpp -o whatsapp_list

###  Usage
- **Create Account:** Enter your desired username and phone number to register a new account.
- **Log In:** Use your username and phone number to access your existing account.
- **Manage Contacts:** Add, delete, update, or view your contact list.
- **Chat:** Initiate conversations with your contacts and save chat history.

### Dependencies
- C++ Standard Library

### Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests. For major changes or new features, please open an issue to discuss your ideas.

### License
This project is licensed under the MIT License.

