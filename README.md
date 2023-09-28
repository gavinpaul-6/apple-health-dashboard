# Apple Health Dashboard using Splunk
This is my project visualizing my fitness data from Apple Health to create dashboard in Splunk

![Splunk-Emblem](https://github.com/gavinpaul-6/apple-health-dashboard/assets/98987388/328da569-7d2e-4834-917c-b0bc185d0683)
![2023-07-29_02-40-20](https://github.com/gavinpaul-6/apple-health-dashboard/assets/98987388/c2921c25-ecff-4a3c-8f2e-4c886a092659)

<h2>Summary</h2>
Dashboards in Splunk are user-friendly graphical interfaces that provide a visual representation of data collected and analyzed by Splunk. They are a central component of the Splunk platform and are used to present real-time or historical data, key performance indicators (KPIs), and insights to users in a concise and meaningful way. Splunk dashboards help users make informed decisions, monitor system health, troubleshoot issues, and gain actionable insights from their data.

<h2>Resources Used</h2>

- Splunk Enterprise (Free trial)
- PowerShell
- iPhone
- Apple Watch

<h2>Training:</h2>

I started my journey through a combination of structured training and hands-on practice. Leveraging Splunk's official training platform, I delved into comprehensive courses and modules designed to equip me with the skills needed to harness the full potential of this tool. Next, I also enrolled in Hailie Shaw's ["Zero to Power User" Udemy course](https://www.udemy.com/course/splunk-zero-to-power-user/), where I gained insights and practical knowledge from a seasoned Splunk expert. To reinforce my learning, I dedicated ample time to hands-on practice using TutorialData, honing my ability to navigate through Splunk's data management, search, and visualization features. This was great preparation for the Splunk Core Certified Power User exam.


![20-14376-SPLK-Certification-Badge-Youracclaim com-101_Splunk-Core-Certified-Power-User](https://github.com/gavinpaul-6/apple-health-dashboard/assets/98987388/1adf77ce-9a75-4fb0-8c07-cf630f14ca3c)

<h2>Converting XML file to CSV</h2>
After successfully saving the document onto my desktop and unzipping the file, I opened PowerShell and ran a Python script created by [Test-Driven Data Analysis](http://www.tdda.info/) to convert the data from XML format to CSV.

<h2>Creating an Index and uploading data</h2>
I started off by creating an index and an app. I then uploaded the data that I wanted to create the visualization for. For simplicity I chose StepCount.csv

![step1](https://github.com/gavinpaul-6/apple-health-dashboard/assets/98987388/3a3ac2b9-54c9-4d73-9674-cc9c1d137cb8)

![step6](https://github.com/gavinpaul-6/apple-health-dashboard/assets/98987388/d42859f6-7e3a-4489-be10-b1764fd3d61f)

<h2>Running Searches</h2>

Now that the data was uploaded I was able to run searches to query data. For example, this search explains the date of when I took my first steps.

![step7](https://github.com/gavinpaul-6/apple-health-dashboard/assets/98987388/6628b267-920a-4680-8024-4c7f49184d5c)

After running the search for the data I was looking for I saved it as a dashboard.

![step8](https://github.com/gavinpaul-6/apple-health-dashboard/assets/98987388/c64f46e7-6f78-4d60-be6d-ea4c971e9d3a)

Utilizing the training I learned from Splunk's official website and Hailie's Splunk course,. I was able to customize and build out my dashboard to how I wanted.

![2023-07-29_04-03-45](https://github.com/gavinpaul-6/apple-health-dashboard/assets/98987388/4d2227f1-4973-4934-be63-bcd2af649847)

![2023-07-29_02-40-41](https://github.com/gavinpaul-6/apple-health-dashboard/assets/98987388/57c9081a-add0-4023-91e6-cafe2c04e5fb)


<h2>Conclusion</h2>

In my preparation for the Splunk Core Certified Power User exam, I focused extensively on mastering the creation of dashboards and efficient searches within the Splunk platform. This journey involved a combination of structured learning and hands-on practice. Through Splunk's official training resources, I gained a deep understanding of how to design and customize dashboards to visually represent data effectively. I also honed my search query skills to efficiently retrieve and analyze data, thanks to Hailie Shaw's "Zero to Power User" Udemy course. My practical experience in crafting dashboards and optimizing searches, often using real-world scenarios, has reinforced my knowledge and expertise. As I approach the Power User exam, I am confident in my ability to create impactful dashboards and conduct precise searches, ensuring that I am well-prepared to excel in leveraging Splunk for data analysis and visualization.






