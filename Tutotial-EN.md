![WAZZAP](https://assets.cdn.filesafe.space/HZSeCeo66qW2JN9HroQv/media/d9739e2b-f7c8-485c-8567-ecd39dbb9688.png)


# 🎉 New Command for Buttons and Lists in the Chat System

Hello! 🎉 I have created two new commands for our chat system that will allow you to send **buttons** and **lists** easily. Below, I explain how to use them clearly and simply:

---

## 📌 **Available Commands**

### 1. 🔘 **Button Command**

**📄 Syntax:**

```#Button|Message Text|Option1*id1/Option2*id2/Option3*id3```

**💡 Example:**

```#Button|Hello, how are you?|Good*id_good/Bad*id_bad/Terrible*id_terrible```

**🔍 Explanation:**
- **#Button**: Indicates that you are creating a message with buttons.
- **Message Text**: The message that users will see.
- **Options**: Button options are defined in the format `Text*id` and separated by `/` if there are multiple.

**📲 Result:**
When the user selects an option, it will appear in GHL like this:

```Button: id_bad```

```Bad```

This shows the **type of button**, the **selected ID**, and the **button text**.

---

### 2. 📋 **List Command**

**📄 Syntax:**

```#List|Title|Description|Footer|Option1*Subtitle1*id1/Option2*Subtitle2*id2/Option3*Subtitle3*id3```

**💡 Example:**

```#List|Hello, how are you?|Tell me the truth|Don't be shy|Good*Perfect*id_good/Bad*Very Bad*id_bad/Terrible*Crying*id_terrible```

**🔍 Explanation:**
- **#List**: Indicates that you are creating a message with a list.
- **Title**: The title of the list.
- **Description**: A brief description or instruction.
- **Footer**: Additional information at the end of the message.
- **Options**: List options are defined in the format `Text*Subtitle*id` and separated by `/` if there are multiple.

**📲 Result:**
When the user selects an option, it will appear in GHL like this:

```List: id_good ```

```Good```

This shows the **type of list**, the **selected ID**, and the **option text**.

---

## 📝 **Quick Summary**

- **🔘 #Button**: Creates a message with buttons.
  - **Option Format**: `Text*id`
  
- **📋 #List**: Creates a message with a list.
  - **Option Format**: `Text*Subtitle*id`

**✨ Tips:**
- You can add multiple options by separating them with `/`.
- Make sure to follow the correct format so that the system recognizes and processes your commands properly.

---

I hope this guide is very helpful to you! 🚀 If you have any questions or need further assistance, feel free to contact me. Happy coding! 😊
