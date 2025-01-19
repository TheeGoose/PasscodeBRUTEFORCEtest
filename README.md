# Brute-Force Safe Cracker

This project is a brute-force safe-cracking simulation written in Python. It systematically guesses a numeric passcode by trying every possible combination until it finds the correct one.

Features

Custom passcode input

Simulated keypress effect for realistic brute-force animation

Supports any numeric passcode length

How It Works

The user enters a numeric passcode.

The script starts from 0000 (or the equivalent for the given length) and iterates through all possible combinations.

It displays each attempt in real-time.

Once the correct passcode is found, the safe is "unlocked."

Installation & Usage

Requirements

Python 3.x

Running the Script

Clone this repository:

git clone https://github.com/TheeGoose/BreadcrumbsPasscodeBRUTEFORCEtest

cd brute-force-safe

Run the script:

python bruteforce_safe.py

Enter a passcode when prompted.

Watch as the brute-force attack finds the correct code.

Example Output

Enter a passcode (digits only): 1234
Starting brute-force attack...
Trying: [0000]
Trying: [0001]
...
Trying: [1234]

SAFE UNLOCKED! The correct passcode is [1234].

Contributing

Feel free to fork this project and make improvements! If you find any issues or have feature suggestions, open an issue or a pull request.

License

This project is licensed under the MIT License.

