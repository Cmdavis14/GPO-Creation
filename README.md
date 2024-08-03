# Group Policy Object (GPO) Creation Lab

## Objective
The objective of this lab was to create and configure a Group Policy Object (GPO) to enforce a password policy within an organization's Active Directory environment. This process aimed to ensure consistent and secure password practices across all users.

## Skills Learned
- **Group Policy Management:** Navigated and utilized the Group Policy Management application to create and edit GPOs.
- **Password Policy Configuration:** Configured password policies, including maximum password age, minimum password length, and complexity requirements.
- **Active Directory Administration:** Enhanced understanding of Active Directory structures and the application of security policies within a domain environment.
- **System Configuration:** Worked within a Windows Server environment, focusing on domain controllers and Group Policy settings.

## Detailed Steps
1. **Access Group Policy Management:**
   - Open the Group Policy Management application. Ensure the system is configured as a domain controller if the application is not visible.

2. **Create a New GPO:**
   - Navigate to the Group Policy Objects folder, create a new GPO named "Password Policy," and confirm.

3. **Edit the GPO:**
   - Right-click the new GPO and select "Edit." Configure settings under:
     - Computer Configuration → Policies → Windows Settings → Security Settings → Account Policies → Password Policy.

4. **Configure Password Policies:**
   - **Maximum Password Age:** Set to 90 days.
   - **Minimum Password Length:** Set to 12 characters.
   - **Password Must Meet Complexity Requirements:** Enable this setting.

5. **Finalize and Apply:**
   - Exit the editor and apply the GPO to users or groups as needed.

