# Manul_Testing
Test Cases										
Project Name	ANPR App QA Testing	Start Date:23sep2025								
Version 	1	End Date:23sep2025								
Test case Design By	Sandeep Yadav	Total Test case:18								
Peer Review By		Pass:Accept 16 all test cases are pass								
Approved By		Fail:16								
										
										
Test ID	Test Scenario	Test cases	Test Data 	Expected Result	Actual Result	Remark/ Observations	Priority(P0/P1/P2)			
Login_Passward_01	Password seen functionality	Verification password visibility issue	Username: admin, Password: Admin@12345	password show be visible when user click on password view	password are hidden after click on see	It's a bug which creates a user issue during login if password get wrong user can't login 	P0			
Login_Sucessfull_02	User valid login 	Enter the correct user id and password	Username: admin, Password: Admin@12345	user directly transfer to dashboard	Pass 	N/A	P0			
Login_UI_03	Spelling validation	Check spelling on login page	N/A	All labels should be correctly spelled	It should Login	UI content should check	P2			
Report_Graphical_Report_03	Page smoothness	Check if Report (Graphical report) page scroll/load is smooth	 Checking from Graphical report page Scroll up and down	Page should scroll smoothly in all directions	 page are not smooth when goes down mouse can't scroll page get stuck after getting down	Performance / UX issue	P0			
Report_Data_04	No data display	Check report data for all date ranges	Select any date range	Report should show data if present	No data displayed for any date	Functional bug or data are not present	P0			
Report_Graphical_Refresh_05	Graphical report refresh	Check refresh in graphical report	Click refresh button	Graph updates / refreshes properly	Refresh not working and not clear due to no data show	Functional bug / UX unclear	P0			
Filter button_06	Filter button check	Check filters for Device, Category, etc.	Click options in filter dropdown	Selecting an option and it should apply correctly	Selecting option collapses next option; Device options disappear	Function and UI issue	P0			
Export / Download_07	Export / Download	It should download in their format	Click export/download	File should download correctly	File downloads correctly	Working	P1			
Referesh_08	Refresh button	Check refresh functionality	Click refresh	Page should reload / update data	no error, no data change	Function issue	P0			
PageUp_Down_09	Page up/down timing	Check page responsiveness while scrolling	Scroll multiple times up/down	Page should be responsive and smooth	Page up/down not smooth	Performance / UX issue	P1			
Report_Refersh_10	Click on Refresh	Check page data are refresh or not	Click Refresh	It should refresh smoothly	Its make page issue where user get stuck , loading time , no filter button work and take time and stop all the function	Function	P0			
Camera_11	Next button  working on camera adjust	Next button on Camera Adjust works	N/A	User should be able to go to next step	Users cannot proceed to next step	Function	P0			
Camera_Associate_12	Camera Associate	Associate details functionality	Click on edit	User can add/edit associate details	No option available	Function/missing feature	P0			
setting_Analytic_13	Analytic Server	Generate device functionality	N/A	Device should generate successfully	Error occurs	Feature broken	P0			
Setting_Hotlist_14	Hotlist	Data update in hotlist	N/A	Data should appear immediately after adding	Data added late	Performance issue	P1			
Setting_User_15	User to Administration	Select/Deselect checkboxes	N/A	Checkboxes should be clickable	Cannot click	UI/functional issue	P0			
Setting_User_16	User to Actions	Add Rule / Rule Set and select category	N/A	User can add rule/rule set & select category	Cannot add/select	Functional issue	P0			
Setting_User_17	User to Actions	Input validation	8-digit number	Invalid numbers should be restricted	8-digit number accepted	Validation missing	P1			
Setting_Logs_18	Logs	Filter and in that Select Device	Filter	Device filter works and refreshes data	Filter not working, data not refreshed	Functional & performance issue	P0			

