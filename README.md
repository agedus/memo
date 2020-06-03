<!-- PROJECT INFO -->
<br />
<p align="center">

  <h1 align="center">Memo</h1>

  <p align="center">
    A bash script to be able to add memories in the commandline
    <br>
    <br>
    Made for linux
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## About The Project

This is made so you can add a memo and watch them from the command line.
You whil also be able to run the memos you save.

<!-- GETTING STARTED -->
## Installing Memos

Here is the simple way of downloading my script and setting it up.
### Installing

1. Clone the git repository
    ```sh
    git clone https://github.com/agedus/memo.git
    ```
2. Enter the folder memo.
    ```sh
    cd memo
    ```
3. Than run the install script(do not run it ass with sudo).
    ```sh
    sh install
    ```
4. Done

### How to use memo
1. For help:
    ```sh
    memo -h/--help
    ```
2. To add a memo:
    ```sh
    memo -a/--add 
    ```
    or:
     ```sh
    memo -a/--add "What ever you want between the quotes"
    ```
3. To delete a memo:
    ```sh
    memo -d/--delete
    ```
    or:
    ```sh
    memo -d/--delete <line number/numbers/all>
    ```
4. To run a memo:
    ```sh
    memo -r/--run
    ```
    or:
    ```sh
    memo -r/--run <line number/numbers>
    ```
5. To uninstall the program:
    ```sh
    memo -u/--uninstall
    ```
    
