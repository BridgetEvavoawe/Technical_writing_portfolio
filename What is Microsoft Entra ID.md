# What is Microsoft Entra ID, and why did Microsoft rebrand Azure AD?







[Microsoft Entra ID](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*YsR4AN5BZedZaC2dXHm7_g.png)

If you’ve ever worked with Microsoft services, you’ve probably heard of Azure Active Directory (Azure AD). Recently, Microsoft renamed it to Microsoft Entra ID, and this has left many — especially IT professionals and Administrators — feeling confused or frustrated.

In this article, I will explain the following:

- What is Microsoft Entra ID?
- Why did Microsoft rename it?
- What does the update mean for learners and everyday users?
  
### What is Microsoft Entra ID?
Microsoft Entra ID, formerly known as Azure AD, is Microsoft’s cloud-based service that is responsible for identity and access management. It provides a secure environment that organizations use to control who has access to their internal or external resources, thereby protecting their data.

It supports the Zero Trust security model, which means that whenever an employee, guest, or even business partner tries to access the organization’s resources, they are not automatically trusted. Instead, they must prove their identity every time before gaining access. This is a crucial protection mechanism that safeguards data.

Think of it this way:

Imagine you are at an airport and about to travel. Before you are allowed to board the plane, you must provide the necessary credentials to prove that you ought to be on that plane. This could include;

- Identity Card.
- Passport.
- Visa.
  
In this scenario, the airline staff who check your credentials represent **Microsoft Entra ID**. Once you can provide all the necessary credentials, you are good to go. If the reverse is the case, you are not trusted and won’t be allowed on the plane.

Similarly, Microsoft Entra ID acts as a **gatekeeper** between users (employees, guests, or business partners) and the organization’s resources. It verifies Identities and ensures that only trusted users can gain access.

### Why did Microsoft rebrand Azure AD?

[Azure AD rebranded to Microsoft Entra ID](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*VWcDaUqCZaHsCjgOE_420g.png)

According to [Microsoft](https://learn.microsoft.com/en-us/entra/fundamentals/new-name#:~:text=As%20part%20of%20our%20ongoing%20commitment%20to%20simplify%20secure%20access%20experiences%20for%20everyone%2C%20the%20renaming%20of%20Azure%20AD%20to%20Microsoft%20Entra%20ID%20is%20designed%20to%20make%20it%20easier%20to%20use%20and%20navigate%20the%20unified%20and%20expanded%20Microsoft%20Entra%20product%20family.), the name was changed from Azure AD to Microsoft Entra ID to provide a more consistent experience for users. The new name helps people to easily find and use all the tools that belong to the Microsoft Entra family in one place.

Here is the thing:

Microsoft has other tools that all belong to the **Entra family**.


Originally, Azure Active Directory (Azure AD) was Microsoft’s main identity and access management service in the cloud. Although other tools related to Identity and permissions existed, they weren’t grouped under a single name like **Microsoft Entra**.

In **2022**, Microsoft realized that Identity and access management had grown beyond just Azure AD, so they introduced a new umbrella brand — **Microsoft Entra**— to bring all their identity, permissions, and access tools together.

Azure AD became a part of this family, but still retained its old name for a while.

Then, in **2023**, Azure AD was renamed to **Microsoft Entra ID** in order to have a consistent naming structure across all Microsoft Entra products.

Here is another reason:

Remember, Azure AD is Microsoft’s cloud-based identity service, but there is also an on-premises version called **Active Directory** (notice how similar the names are).

Because their names were so similar, many people often got them confused.

The new name — **Microsoft Entra ID**— helps reduce that confusion and makes it clear that this is the **cloud-based identity solution**.

### What has changed (and what hasn’t)
**What has changed?**

Just the name.

**What hasn’t changed?**

The name may have changed, but everything else remains the same. All your existing setups, connections, and apps will keep working just as before.

Nothing important has changed — your login links, APIs, PowerShell commands, and Microsoft Authentication Libraries (MSAL) will still work. The update is mainly about the name and look, and not about how things function.

If your team already uses Azure AD, you don’t need to do anything. You can continue using it as usual and gradually start using the new name, **Microsoft Entra ID**, in your documents and training.

### Why does it matter to learners and businesses?
**For learners:**

If you’re studying or working with Microsoft tools, you will now see **Microsoft Entra ID** instead of **Azure AD**, but the concepts remain the same. So, you don’t have anything to worry about; just get familiar with the new name.

**For Businesses:**

Nothing technical has changed; all systems, apps, and settings will continue to function as they did before. So, businesses don’t need to make any adjustments.

## CONCLUSION
Microsoft Entra ID is simply the new name for Azure Active Directory(Azure AD). Although the name may have changed, its features and functionalities remain the same.

The rebranding doesn’t change how the service works; it only aligns Azure AD with Microsoft’s broader Entra family. This makes it easier to understand and use, especially as Microsoft continues to expand its identity solutions across multiple clouds and platforms.

Now that you understand what Microsoft Entra ID is and why Microsoft renamed it, the next step is to understand the core building blocks that make the system work.

In the next article of this series, I’ll walk you through the essential components of Entra ID.