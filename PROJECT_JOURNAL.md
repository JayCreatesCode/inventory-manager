# Inventory Manager Project Journal 

## Project Purpose
I am building an inventory manger for a fictional small business. The application will track stock and create reorder tickets when an item's quantity reaches or falls below its reorder threshold. 

## Intended Users
Nontechnical employees who need to monitor inventory, record stock changes, and manage reorder tickets. It should be used by employees who record inventory and then also by the party responisble for ordering new supplies.

## Learning goals
Learn Python, SQL, database design, user interface development, testing, Git, and GitHub by building a complete application. 

## Starting Point
I use Ubuntu paired with VSCode. Right now I have a general understanding of python and SQL from college courses I've taken, but other than that no real world experience building an application from start to finish, This project will serve as my first developed project from start to finish and act as a portfolio project to show my skills and abilities. 

## Schedule
I want this to be completed by six weeks. I can spend up to four hours per day during this first week of 10/14-10/20, after that each day will only recieve a dedicated 2 hour block at a frequency of 4 days a week until the final week six. 

## Working Agreement
I will write all project code myself, while personally researching methods of writing and developing when I don't know something, as this project also should serve as a formal foundation to build my current coding skills on. I will document each work session and explain what I learned along the way. 

## Session 1 - Project Setup
### Completed
- Defined the intial project purpose and learning goals.
- Created the project folder
- Created this journal to document the building journey

## Next Steps
- Finalize the first version's feature list and business rules.
- Check python and Git availability 

## Version 1 requirements

### Required features
- Display and search inventory.
- Add Inventory items with a unique identifier (SKU), name, quantity, and reorder threshold. 
- Record stock recieved and removed
- Keep a history of stock changes.
- Automatically create a reorder ticket when stock is at or below the item's reorder threshold. 
- Prevent multiple open reorder tickets for the same item. 
- Allow users to resolve a ticket after stock rises above the reorder threshold.
- Display low-stock items and open tickets in a friendly UI.

### Business Rules
- Each SKU must be unique.
- Quantities and thresholds must be nonnegative whole numbers.
- Stock cannot be removed if it would make the quantity negative.
- An item added at or below its threshold needs a reorder ticket. 
- A resolved ticket remains in the history. 
- If stock falls to the threshold again after a ticket is resolved, a mew ticket can be created. 


### Outside version 1
- Real purchasing or supplier orders. 
- SAP integration
- Barcode scanning
- Multiple warehouses
- User accounts and permissions

### Definition of done
- All required features work with fictional inventory data. 
- Important business rules have automated tests.
- The interface explains invalid inputs clearly. 
- The GitHub repository includes setup instructions. 
- Another person can follow the instructions and run the app. 
- Screenshots and a short demonstration show how it works. 
- I can explain the code and the main design decisions. 

## Tools Verified
- Python 3.14.4
- Git 2.54.0
- Checked installation using python3 --version and git --version. 

## Git setup
- Verfieid that Python and Git are installed. 
- Initialized the project as a Git repository. 
- Named the main development branch 'main'

### Git concepts
- Git tracks changes made to project files. 
- A repository is a project folder whose history is tracked by Git. 
- An untracked file is visible to Git but is not yet included in Git's history. 
- An untracked file is visible to Git but is not yet included in Git's history. 
- Staging selects the changes that will go into the next commit. 
- A commit is a saved checkpoint in the project's history. 
