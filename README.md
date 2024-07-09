# Automation of  Window’s Calculator 

Automating the Windows Calculator using UI Studio was a fascinating project that aimed to streamline repetitive tasks and improve efficiency. The process began with a meticulous analysis of the calculator's interface and functionality. UI Studio's robust capabilities allowed for the creation of detailed automation scripts that mimicked human interactions with precision. Through the utilization of UI elements such as buttons, text boxes, and dropdown menus, the calculator's operations were automated seamlessly.
The project's development phase involved configuring UI Studio to recognize and interact with specific elements of the Windows Calculator interface. This included identifying the exact coordinates of buttons and fields, defining input methods for numerical values, and scripting logical operations such as addition, subtraction, multiplication, and division. UI Studio's intuitive drag-and-drop interface made it accessible to map out workflows and integrate error handling mechanisms to ensure robust performance under varying conditions.
Upon completion, the automated solution significantly enhanced operational efficiency by eliminating manual input errors and reducing the time required for routine calculations. The UI Studio's ability to run scripts in the background allowed for uninterrupted multitasking, enabling users to focus on more strategic tasks while calculations proceeded autonomously. Overall, automating the Windows Calculator with UI Studio not only showcased the power of robotic process automation (RPA) but also underscored its potential to revolutionize workflow efficiency across various domains

# Solution:
1.	Create a new sequence in UI path studio.
2.	Use input dialog for user to enter the first number .
3.	Then validate the number.
4.	Use another input dialog for user to enter the second number.
5.	Then validate the number.
6.	Use an input dialog  with  Multiple Choice option to choose the operation to be performed .( +, -, *, /)
7.	Next create a sequence to calculate the function created by user.
8.	This can be achieved by using sub sequences.
9.	‘Use application’, is used to open the Calculator application.
10.	 ‘For Each’, is used to create the sequence for selecting the number using the mouse by the automation.
11.	 ‘Else if’ conditional is used to select based on the operation used.
12.	Second number is entered in similar manner.
13.	Now ‘=’ is selected and function is calculated successfully.
14.	Finally a ‘message box’ is used to display the result.
