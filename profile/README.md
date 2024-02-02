# 📋Coding Standards

✨ **Coding Best Practices 🚀**

- Adhering to these coding practices is crucial for our team to reap numerous benefits, including heightened code readability, improved maintainability, increased code reusability, better collaboration, elevated code quality, and an overall enhancement in software reliability and performance. 💻✨

To streamline the process, consider utilizing a [Node.js application for generating blueprints](https://github.com/eDigits/FilesTemplatesGenerator) tailored to different script types. Additionally, employ the Prettier - Code formatter extension to ensure consistent code formatting throughout the development process. 🛠️

### **Key Practices to Incorporate 🌟**

📝 **Naming Conventions:**

- All function,variables names should adhere to the lower camel case convention. 🐪
- Constant variable’ names are capital
- Avoid using single characters as variable names. 🚫
- Clearly indicate the data type and description within variable names. 📊

🔠 **Variable Prefixes:**

- String variables: Prefix with "string," e.g., stringTitle. 🏷️
- Integer variables: Prefix with "int," e.g., intTotalCount. 🧮
- Float variables: Prefix with "float," e.g., floatPrice. 🌊
- Boolean variables: Prefix with "bool," e.g., boolIsDone. 💡
- Array variables: Prefix with "arr," e.g., arrPhoneCalls. 📦
- Object variables: Prefix with "Obj," e.g., ObjNewPet. 🧸
- Record variables: Prefix with "record," e.g., recordCustomer. 🗃️
- Date variables: Prefix with "date," e.g., dateFirstBillingDate. 📅

📘 **SuiteScript Guidelines:**

- Utilize SuiteScript 2.1, employing "let" or "const" declarations and avoiding the usage of "var." 🚀
- Follow a recommended filename convention for multi-account SuiteScript code. 📝
    
    📑 **Script Types and Naming Conventions:**
    
    - Consider the recommended filename convention: <Company Name/Abbreviation><Script Type>.js. 📂
    - The name after the script type will follow PascalCase
    - Suggested Script Types 📜:
        - Client Script ➔ (CS) 🔧
        - User Event Script ➔ (UE) 🔄
        - Suitelet Script ➔ (SL) 📑
        - Restlet Script ➔ (RL) 🌐
        - Portlet Script ➔ (PL) 🖼️
        - Scheduled Script ➔ (SC) 🗓️
        - MapReduce Script ➔ (MR) 🗺️
        - GL Plugin ➔ (GL) 💡
        - Workflow Action ➔ (WA) 🔄
        - Mass Update Script ➔ (MU) 🔄
        - Bundle Installation ➔ (BI) 📦
    - For instance, use EDC-CS-SetTaxable.js. 🌐
- Use descriptive script IDs and deployments IDs. No more customscript1 and customdeploy1.🆔

🚨 **Error Handling:**

- Enclose functions within try-catch blocks for effective error handling. 🚧

🌐 **URL Handling:**

- Avoid hard-coding URL links; instead, utilize the N/url module to construct URLs. 🔗

📢 **Logging Best Practices:**

- Ensure log messages convey meaningful business information, including record ID, record type, and other relevant details. 📋
- Log important steps in each script as Audit entries for comprehensive debugging. 🚦
- You can Use the logger function added by the NodeJS generator

📦 **Code Organization:**

- Break down your code into reusable modules and functions to enhance organization, maintainability, and reusability. 🧩
- Craft a brief script description at the start of the file within JSDocs 📝

🛠️ **Linting and Formatting:**

- Incorporate [Prettier](https://prettier.io/) for code formatting.
- Install the Prettier extension in VSCode and configure it globally to auto-format on saving.

By integrating these practices, our team will not only produce cleaner and more efficient code but will also establish a foundation for streamlined collaboration and robust software development. Regularly revisit and refine these practices based on evolving project requirements and emerging best practices in Netsuite development. 🚀🌟
