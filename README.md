Columns common to all four years (2022–2025)

33 columns exist in every survey year. 

Short explanation of each:

Identification & filtering
Column 	Meaning 	Note
ResponseId 	ID number of each respondent 	                                              Only unique within one year, not across years
MainBranch 	Relation to coding (e.g. developer by profession, learning to code, hobby) 	Useful for filtering professional developers
Employment 	Employment status (full-time, part-time, freelancer, student, …) 	          Can contain several answers separated by ; – categories changed in 2025
Target
Column 	              Meaning 	                                                    Note
ConvertedCompYearly 	Total yearly compensation, converted to US dollars 	          Target variable
CompTotal 	          Compensation as entered, in the respondent's own currency 	  Not comparable across countries – would leak the target
Currency 	            Currency used for CompTotal 	                                Only describes CompTotal – would leak the target

Person
Column 	    Meaning 	                                                    Note
Age 	      Age group (e.g. "25-34 years old") 	                          Categories, not exact numbers
Country 	  Country of residence 	                                        Many categories – rare countries may need grouping
EdLevel 	  Highest level of formal education 	                          Long text labels
LearnCode 	How the person learned to code (books, online, school, …) 	  Multi-select (;-separated)

Experience
Column 	    Meaning 	                                         Note
YearsCode 	Years of coding in total (including education) 	   Text values like "Less than 1 year" in 2022–2024; numeric in 2025
WorkExp 	  Years of professional work experience 	           Numeric

Job
Column 	            Meaning 	                                                           Note
DevType 	          Job role (e.g. back-end developer, data scientist) 	                 Can contain several roles in some years
OrgSize 	          Size of the company (number of employees) 	                         Categories
ICorPM 	            Individual contributor or people manager 	                           Two categories
RemoteWork 	        Work arrangement: remote, hybrid or in-person 	                     Labels differ between years (e.g. "Fully remote" vs "Remote")
PurchaseInfluence 	How much influence the person has on technology purchases at work 	 Categories

Technology (all multi-select, ;-separated)
Column 	                        Meaning
LanguageHaveWorkedWith 	        Programming languages used in the past year
LanguageWantToWorkWith      	  Programming languages the person wants to use next year
DatabaseHaveWorkedWith      	  Databases used
DatabaseWantToWorkWith 	        Databases the person wants to use
PlatformHaveWorkedWith        	Cloud platforms used (AWS, Azure, …)
PlatformWantToWorkWith        	Cloud platforms the person wants to use
WebframeHaveWorkedWith  	      Web frameworks used (React, Django, …)
WebframeWantToWorkWith  	      Web frameworks the person wants to use
OfficeStackAsyncHaveWorkedWith 	Asynchronous collaboration tools used (Jira, Confluence, …)
OfficeStackAsyncWantToWorkWith 	Asynchronous collaboration tools the person wants to use
OpSysPersonal use 	            Operating systems used privately
OpSysProfessional use         	Operating systems used at work

Stack Overflow usage
Column 	        Meaning
SOAccount 	    Whether the person has a Stack Overflow account
SOVisitFreq 	  How often they visit Stack Overflow
SOPartFreq    	How often they participate (ask/answer)
SOComm        	Whether they feel part of the Stack Overflow community

Observations
    YearsCodePro (years of professional coding) exists in 2022–2024 but not in 2025 → WorkExp is the common experience column.
    Several columns have different answer categories in different years (e.g. RemoteWork, Employment) → they need harmonising before combining the years.


