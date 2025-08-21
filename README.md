# UTC Clock

A simple Flask-based web application that displays the current UTC time and Indian Standard Time (IST).

## Motivation

When I was working on a project where I was constantly testing with UTC time for scheduling tasks, I was getting fed up of doing `(Get-Date).ToUniversalTime()` in PowerShell each time. This gave way to the idea of creating a UTC clock. I also added IST since I am from India.

## Features

*   Displays the current time in UTC.
*   Displays the current time in IST.
*   The IST clock is 35% smaller than the UTC clock.
*   The clocks are updated every second.

## Usage

1.  Clone the repository:

    ```
    git clone https://github.com/Smugcurve13/utc-clock.git
    ```

2.  Install the dependencies:

    ```
    pip install -r requirements.txt
    ```

3.  Run the application:

    ```
    python app.py
    ```

4.  Open your web browser and go to `http://localhost:5005`.
