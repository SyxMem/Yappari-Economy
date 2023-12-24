
<img src="https://github.com/SyxMem/Yappari-Economy/blob/main/Yappari_Economy.jpg?raw=true" />

# Layer 7 Attack Tool Documentation
Overview
The Layer 7 Attack Tool is a multi-threaded application designed for conducting HTTP-based attacks on specified URLs. It supports both GET and POST requests, allowing users to simulate high traffic to a target server.

# Features
GET and POST Attacks: The tool supports two types of attacks, GET and POST, depending on the user's requirements.
Random Number Generation: You can include a special syntax $RandNumZ(length) in your POST data, and the tool will replace it with a randomly generated number of the specified length.

# Usage Instructions

1. User Input
The tool prompts the user to provide the following information:

```yaml
URL: Enter the target URL (e.g., https://www.attackme-onichan.com).
Number of Threads: Specify the number of threads you want to use for each attack.
Number of Attacks: Define how many times you want to repeat the attack.
Type of Attack (POST or GET): Choose either POST or GET based on your testing requirements.
If POST is selected, you will be prompted to enter POST data.
```

2. Generating Random Numbers
If you choose to perform a POST attack and include the special syntax $RandNumZ(length) in your POST data, the tool will replace it with a randomly generated number of the specified length.

3. Starting the Attack
After entering all the required information, the tool will display the configured settings and wait for 5 seconds before initiating the attack. This gives you time to cancel if needed.

4. Output
The tool outputs the results of each HTTP request, including any errors encountered during the process. Note that error messages from cURL are displayed in case of issues.

# Example
### User Input:
```yaml
Enter the URL you want to attack (ex. https://www.attackme-onichan.com): https://www.example.com
How many threads you want to perform for each attack: 10
How many times you want to attack: 100
What type of attack you want to send (POST or GET): POST
(example: phone=omagahman&phoneNumber=999)
Enter POST data: user=$RandNumZ(5)&action=login
```

### Generated POST Data:
```yaml
user=74829&action=login
```

### Attack Output:
```yaml
Threads: 10
Attacks: 100
Type of Attack: POST
Starting in 5 seconds...
(Output of individual HTTP requests will be displayed during the attack.)
```

# Notes
Ensure you have the necessary permissions to conduct tests on the specified target URL.
Use responsibly and only on systems you have explicit permission to test. either way i don't really care

# Author
Author: RealSyferX

# Disclaimer
I'm not responsible if you put many 1 trillion threads and breaking your devices, if you blame me.. i point my finger at you and lmao.

# Support
For any issues or inquiries, please contact the author: icantbelieveyouwanttomailmelmao@lol.com

Feel free to customize the documentation based on your preferences and requirements.
