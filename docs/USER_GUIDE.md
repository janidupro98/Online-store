# User & Admin Guide

## 👤 For Regular Users
1.  **Registration:** Click "Register" on the home page.
2.  **Browsing:** Scroll through the dynamic product grid or use the search bar.
3.  **Shopping:** Click "Add to Cart" on any product.
4.  **Checkout:** Go to the Cart page and click "Checkout" to generate your bill.

## 🛠️ For Administrators
- **Login Credentials:**
    - **Email:** `admin@store.com`
    - **Password:** `password123`

- **Adding Products:**
    - Access the "Add New Product" button (Visible only to Admins).
    - Fill in details and upload an image.
- **Management:** 
    - Admins can delete any item from the inventory directly from the home grid.

## ⚠️ Troubleshooting
- **Image flickering:** Resolved via nullifying the local `onerror` handler in Thymeleaf templates.
- **Login Issues:** Ensure you are using the full email address.
