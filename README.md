#include <iostream>
using namespace std;

int main() {
    int playerHealth = 50;
    int bossHealth = 100;

    cout << "Battle Start! Player HP: " << playerHealth << " | Boss HP: " << bossHealth << endl;

    if (playerHealth > bossHealth) {
        cout << "Player is stronger and wins easily!" << endl;
    } else if (playerHealth == bossHealth) { // ✅ Fixed: corrected variable name and condition
        cout << "It’s a tie, sudden death mode begins!" << endl; // ✅ Fixed: uncommented line
    } else {
        cout << "Boss overpowers the player!" << endl;
    }

    return 0;
}
