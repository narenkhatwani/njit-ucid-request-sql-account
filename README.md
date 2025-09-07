Request Access to SQL/Oracle Account and steps to get SQL developer up and running requesting an Account

Students, faculty, and staff can request an **Oracle** or **MySQL** account using the **MyUCID Management** website:

1. Go to [http://myucid.njit.edu](http://myucid.njit.edu).
2. Select **Manage Your UCID**.
3. Enter your **UCID username** and click **Next**.
4. Enter your **UCID password** and click **SIGN IN**.
5. Click on the **REQUESTS** tab.
6. Click the **REQUEST ACCESS** tab.
7. Select **Accounts** from the **Access Catalog** drop-down menu and click the **NEXT** button.
8. Select the account(s) you would like created (**Oracle** and/or **MySQL**) and click **DONE**.
9. Indicate how long you will need access.  
   > **Tip:** We suggest selecting **Permanent**.
10. Click the **SUBMIT REQUEST** button.

> **Note:** Requests are processed automatically.

---

# Reset Your Academic Database Password (Oracle and MySQL)

1. Go to [http://myucid.njit.edu](http://myucid.njit.edu).
2. Click **Manage Your UCID**.
3. Enter your **UCID** and click **NEXT**.
4. Enter your **UCID password** and click **SIGN IN**.
5. Click the **RESET PASSWORD** link located at the top.
6. You will see a table with a list of accounts that will change.
7. Type your **new password** twice for verification.
8. Click on the **RESET PASSWORD** button to finish.


# How to Use Oracle for CS331/CS631/CS632/CS434

## **Step 1: Download SQL Developer**

Download **SQL Developer** from here:  
[https://www.oracle.com/tools/downloads/sqldev-downloads.html](https://www.oracle.com/tools/downloads/sqldev-downloads.html)

1. **Accept the License Agreement.**
2. Click on the appropriate **Download** link for your operating system.
3. You will need to **create an Oracle account**.  
   > **Tip:** Use your **NJIT email address** for the registration.
4. Log in to your Oracle account.
5. Once downloaded:
   - Click on the downloaded **ZIP file**.
   - Close the **RAR options menu** if it appears.
   - Double-click on the `sqldeveloper` directory.
   - Double-click on the `sqldeveloper.exe` file.
   - If prompted about additional installations, click **No**.
   - **Uncheck** the **Allow** button and click **OK**.

---

## **Step 2: Set Up Your Oracle Password**

### **NJIT Passwords**
- If there’s an **NJIT UCID password issue**, reset it here:  
  [http://myucid.njit.edu](http://myucid.njit.edu)

> **Important:**  
Your **Oracle database password** must be **different** from your **UCID password**.

### **How to Get Your Oracle Database Password**
- Use the **Database Password Assistant**:  
  [https://ist.njit.edu/database-password-assistant/](https://ist.njit.edu/database-password-assistant/)

### **Working from Home**
- To connect to Oracle off-campus, **install the NJIT VPN**:  
  [http://telecom.njit.edu/vpn/](http://telecom.njit.edu/vpn/)

---

## **Step 3: Connect to Oracle**

1. In the **Connections** panel (upper left window), **right-click** on the word **Connections**.
2. Select **New Connection**.
3. **Create a name** for this connection.  
   > Example: `CS331_Oracle`
4. Enter the following details:
   - **Username** → Your **UCID** (e.g., `ce85` → replace with yours)
   - **Password** → Your **Oracle database password** (generated earlier)
   - **Hostname** → `prophet.njit.edu`
   - **Port** → `1521` *(default, leave as-is)*
   - **SID** → `course`
5. **Authentication** → None required.
6. Click **Connect**.

---

## **Step 4: Start Using Oracle**

- Once connected, you should now see a **Worksheet** window on the right side.
- You can begin writing and executing your **SQL queries** here.

---

### **Quick Links**
- [Download SQL Developer](https://www.oracle.com/tools/downloads/sqldev-downloads.html)
- [Reset UCID Password](http://myucid.njit.edu)
- [Oracle Database Password Assistant](https://ist.njit.edu/database-password-assistant/)
- [Install NJIT VPN](http://telecom.njit.edu/vpn/)
