# reads-excel-from-url
Will list links from a website based on condition and read them without a need to download them one by one.

- There are only required .xlsx tables appearing on this particular website. Therefore, the condition used identifies only these required Excel files.
- Refine the condition in a for loop according to your html tags, which contain the tables (files/elements) you want to access or list.
- Later in the process, I read these files using read function from Pandas library in Python, and perform fundamental data cleansing operations in order to retrieve required information
