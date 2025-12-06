# user-configuration-manager-in-python
# User Configuration Manager 🛠️

A simple Python project that manages user configuration settings such as theme, notifications, and volume.  
This project was built as part of the **FreeCodeCamp Python Certification** to practice dictionary operations, string handling, and control flow.

---

## Features

- Add new settings with validation
- Update existing settings
- Delete settings
- View all current settings in a readable format
- Case-insensitive handling of keys and values
- Clear and user-friendly feedback messages

---

## Initial Configuration

The project starts with a sample settings dictionary:

```python
test_settings = {
    "theme": "dark",
    "notifications": "enabled",
    "volume": "high"
}
