# EDC Tech Team 💻🚀

## **Code Practices 🚥**

By trying to follow these code practices, the team can achieve benefits such as improved code readability, enhanced maintainability, increased code reusability, better collaboration, higher code quality, and overall improved software reliability and performance.Therefore, it is highly recommended to kindly follow these practices when writing code in order to maximize these advantages and deliver high-quality software solutions.

- **You can install [nodejs app at](https://github.com/eDigits/FilesTemplatesGenerator) for generating blueprints for different script types.**
- **Utilize the [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) extension for code formatting.**
- **Ensure that all function names adhere to the lower camel case convention.**
- **Avoid using single characters as variable names.**
- **Assign variable names that indicate the data type and describe the data stored within them. For instance:**
    - **String variables should be prefixed with "st," such as stTitle.**
    - **Integer variables should be prefixed with "int," such as intTotalCount.**
    - **Float variables should be prefixed with "fl," such as flPrice.**
    - **Boolean variables should be prefixed with "b," such as bIsDone.**
    - **Array variables should be prefixed with "arr," such as arrPhoneCalls.**
    - **Object variables should be prefixed with "Obj," such as ObjNewPet.**
    - **Record variables should be prefixed with "rec," such as recCustomer.**
    - **Date variables should be prefixed with "dt," such as dtFirstBillingDate.**
- **Utilize SuiteScript 2.1 instead of SuiteScript 2.0 or
SuiteScript 2.x, employing "let" or "const" declarations and avoiding
the usage of "var."**
- **When writing SuiteScript code for multiple accounts, consider following the recommended filename convention: <Company
Name/Abbreviation>*<Script Type>*<Requirement Description>.js. For example, EDC_CS_SetTaxable.js.**
    
    The suggested Script Types are as follows:
    
    - **CS – Client Scripts**
    - **UE – User Events**
    - **SL – Suitelet**
    - **RL – RESTlet**
    - **PL – Portlet**
    - **SC – Scheduled**
    - **MR – Map/Reduce**
    - **Gl – SuiteGL**
    - **WA – Workflow Action**
    - **MU – Mass Update**
    - **BI – Bundle Installation**
- **Enclose your functions within try-catch blocks.**
- **Avoid hard-coding URL links; instead, utilize the N/url module to construct URLs.**
- **Ensure that log messages in the script convey meaningful
business information, including record ID, record type, and other
relevant details. Each log message should provide a clear understanding
of the script's intended functionality.**
- **Log important steps in each script as Audit entries.**
- **Thorough logging enhances code readability and facilitates effective issue and error debugging.**
- **Break down your code into reusable modules and functions to promote code organization, maintainability, and reusability**
