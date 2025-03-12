## **Augmented Descope MFA Login Experience**

This is a **simple authentication demo** that combines **traditional login** (username & password) with **OAuth authentication using Descope** as a custom provider.

🔒 **Multi-step authentication process:**

1. **User logs in with username & password.**
2. **User is redirected to Descope’s MFA flow.**
3. **After OAuth authentication, the app verifies the user's session and grants access.**

## **🚀 Features**

- Showcase magic link MFA with Descope, along with trusted device and passkey functionality
- Augments existing traditional login flow with a seamless OAuth based login experience

## **🖥️ How to Run the App**

### **1️⃣ Clone or Download the Repository**

```sh
git clone https://github.com/descope-dev/amex-gbt-poc-js.git
cd amex-gbt-poc-js
```

### **2️⃣ Start a Local Server**

This app does not require a backend—just run a static file server:

```sh
npx serve .
```

🔹 This will serve the `index.html` file at `http://localhost:3000` or another available port.
# amex-gbt-poc-js
