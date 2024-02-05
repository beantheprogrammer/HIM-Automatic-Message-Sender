# HIM-Automatic-Message-Sender
**This program is availible to Mac users only.**

## Download ##
[HIM Automatic Message Sender.app.zip](https://github.com/beantheprogrammer/HIM-Automatic-Message-Sender/archive/refs/heads/main.zip)

![Example Image](https://drive.google.com/uc?id=1N7suon6Rkk7TrMijGTY1PyeW4jtD6K5Y)

## How to Use ##
First, you will need to download the desired Google Sheet data as a '.csv' file. 

![Example Image](https://drive.google.com/uc?id=1p65uY47AeDr2KbxJW9ne9OGtbBxUkm-b)

Then, open the 'HIM Auto Message Sender' program, where you will be asked to upload this '.csv' file.
Upon uploading the file, a window with four sections will appear.

### Message ###
This segment is straightforward: enter the intended message you wish to send. The message box must not be blank and should not contain only spaces. As this is a professional organization, kindly include your name in your message and avoid sending anything inappropriate.

### Add Filter ###
You will need to provide two inputs: firstly, indicate the column in the Google Sheet containing the data you wish to select, and secondly, specify the targeted value from that particular column.

For instance, if you aim to send a message to every phone number associated with a team captain named Andrew Lau, refer to the example below. In this case, 'TEAM CAPTAIN' corresponds to the column 'AO' in Google Sheets. Therefore, you should choose 'AO' as your Google Sheets column. Next, input 'Andrew Lau' into the 'Targeted Value' box, as this is the team captain you intend to select. 

![Example Image](https://drive.google.com/uc?id=1hWutqB_ylqy6pDeUsKeuwx0BC9Edc0cp)

Upon selecting 'Add Filter,' your designated message will be sent to each volunteer whose team captain is identified as Andrew Lau.

**(Note: If your targeted value is empty, leave the box blank.)**

### Filter List ###
This section displays the filters you've included, providing an option to clear them all and begin anew. Notably, there is a checkbox labeled 'Must meet all requirements.' When activated, every condition in your filter list must be satisfied for the message to be sent to a particular number. Conversely, when deactivated, the message will be sent if at least one condition is met.

![Example Image](https://drive.google.com/uc?id=18TamhkSM5wWdfJFwCKGenl21KP5reWQm)

In the example above, activating 'Must meet all requirements' implies that a number will only receive a text message if it satisfies all of the specified conditions:
1. Column M contains "Andrew Lau"
2. Column K contains "Expo AM"
3. Column R contains "6:15 AM"
4. Column R contains ""

Nevertheless, when 'Must meet all requirements' is deactivated, the system will send a text message to the number if any one of the specified conditions is met.

### Phone Number Column ###
Lastly, in this section, identify the column where the phone numbers tab is listed. However, before proceeding to click "send," there are some important considerations to keep in mind:

- Ensure that you are using the correct and up-to-date '.csv' file; the structure of Google Sheets for Heart in Motion events undergoes constant changes, which may lead to alterations in columns or values.
- Double-check your filters and message; it's crucial to avoid sending messages to the wrong recipients or transmitting incorrect information inadvertently.
- Verify that your 'Must meet all requirements' setting aligns with the specific group of people you intend to text; otherwise, there is a risk of unintentionally sending messages to a larger or smaller audience than intended.
