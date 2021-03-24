<!-- PROJECT INFO -->
<br />
<p align="center">

  <h1 align="center">Memo</h1>

  <p align="center">
    A bash script to add memories in your commandline
    <br>
    <br>
    Made for linux
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## About The Project

This is made so you can add a memo and watch them from the command line.
You wil also be able to run the memos you save.

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
3. Then run the install script(do not run it as with sudo).
    ```sh
    sh install
    ```
4. Done

### How to use memo
1. For help:
    ```sh
    memo -h
    ```
    ```sh
    memo --help
    ```
2. To add a memo:
    ```sh
    memo -a
    ```
    ```sh
    memo --add 
    ```
    or:
     ```sh
    memo -a "What ever you want between the quotes"
    ```
    ```sh
    memo --add "What ever you want between the quotes"
    ```
3. To delete a memo:
    ```sh
    memo -d
    ```
    ```sh
    memo --delete
    ```
    or:
    ```sh
    memo -d <line number or numbers or all>
    ```
    ```sh
    memo --delete <line number or numbers or all>
    ```
4. To run a memo:
    ```sh
    memo -r
    ```
    ```sh
    memo --run
    ```
    or:
    ```sh
    memo -r <line number/numbers>
    ```
    ```sh
    memo --run <line number/numbers>
    ```
5. To uninstall the program:
    ```sh
    memo -u
    ```
    ```sh
    memo --uninstall
    ```
    
