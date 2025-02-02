# 📌 How to Fetch Your `Bitmoji-Token`

## Step-by-Step Guide  

1. **Open Your Browser**  
   - Navigate to [Bitmoji.com](https://www.bitmoji.com).  
   - Log in using your **Snapchat** account.  

2. **Change Your Outfit**  
   - Select any **pre-made outfit** and apply it.  
   - This step is crucial for triggering the necessary network requests.  

3. **Open Developer Tools (Inspect)**  
   - Right-click anywhere on the page and select **Inspect** or press `F12`.  
   - Go to the **Network** tab.  

4. **Save Your Outfit**  
   - While the **Inspect Console** is open, **save your outfit**.  
   - The site will **redirect** you to a page with multiple buttons.  

5. **Click "Edit Avatar" or "Change Outfit"**  
   - This action will generate multiple network requests.  

6. **Find the "avatar" Request**  
   - In the **Network Tab**, look for a request named **"avatar"**.  
   - Click on it to view its details.  

7. **Locate the `Bitmoji-Token`**  
   - Scroll down to the **Headers** section.  
   - Look for a header labeled **"Bitmoji-Token"**.  
   - It will be in this format:  
     ```plaintext
     Bitmoji-Token: ac293848bb3595u749IRm3857493
     ```  

8. **Copy & Save Your Token**  
   - Copy the **Bitmoji-Token** for use in Nylon requests.  
   - Keep it private to prevent unauthorized access, Make sure to set this in the Nylon Textfield.  

---

✅ **Now you have your `Bitmoji-Token` ready to use!**  
