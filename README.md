### **Repository Description**  

**Laravel Toastr Notifications**  

This repository provides a simple implementation of **Toastr.js** notifications in a Laravel project. It dynamically displays success, error, info, and warning messages based on Laravel session flash data. The notifications are positioned at the top-right corner of the screen for better visibility.  

### **Features:**  
- **Success Notification** → Displays a green toast for successful actions.  
- **Error Notification** → Shows a red toast when an error occurs.  
- **Info Notification** → Provides an informational message.  
- **Warning Notification** → Alerts the user with a warning message.  
- **Dynamic Flash Messaging** → Fetches session messages and displays them automatically.  

### **Usage:**  
1. Ensure you have **Toastr.js** and **jQuery** included in your Laravel Blade template.  
2. Use Laravel's `session()->flash()` method to set messages in controllers.  
3. The script automatically triggers **Toastr** notifications when a session message is available.  

This implementation enhances **user experience** by providing real-time feedback on user actions. 🚀