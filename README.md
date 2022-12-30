# TRELLO PowerUp: Card Age Tracker

This Trello power-up adds a button to every card on a board that displays the number of days since the card was created. When clicked, the button calculates the number of days and displays the result as a badge on the card.

## Installation

1. Clone or download this repository.
2. Host the `index.html` file on a web server or hosting service, such as Netlify.
3. In Trello, go to the board settings page and click the "Power-Ups" tab.
4. Click the "Custom Power-Ups" button and add the URL of the hosted `index.html` file.
5. The power-up will now be available on every card on the board.

## Usage

To use the power-up, click the "Days since" button on a card. The number of days since the card was created will be displayed as a badge on the card.

## Customization

You can customize the appearance of the badge by modifying the `color` property in the `card-badges` section of the code. Simply change the value of the `color` property to a valid CSS color value, such as "red" or "#FF0000".

You can also customize the icon that is displayed on the button by replacing the `./calender.png` file with your own icon. Just make sure to update the `icon` property in the `card-buttons` section of the code with the correct path to your icon file.

I hope this helps! Let me know if you have any other questions or need further assistance.
