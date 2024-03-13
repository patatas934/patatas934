#include 
#include 
#include 

using namespace std;

// Function prototypes
void displayMenu();

int main() {
    char choice;

    do {
        displayMenu();
        cout << "Enter your choice: ";
        cin >> choice;
        cin.ignore(); // Clear input buffer

        switch (choice) {
            case '1':
                // new();
                break;
            case '2':
                // delete();
                break;
            case '3':
                //search();
                break;
            case '4':
                //displayAll();
                break;
            default:
                cout << "Invalid choice. Please try again." << endl;
        }
    } while (choice <=6);

    return 0;
}

void displayMenu() {
    cout << "\nAvailable operations:\n";
    cout << "1. Add New \n";
    cout << "2. Remove \n";
    cout << "3. Search \n";
    cout << "4. Display All \n";
    cout << "5. Exit\n";
}
