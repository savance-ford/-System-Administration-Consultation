# System-Administration-Consultation

## 1. Learning Goals:

1. Use the systems administration concepts you learned in the course to provide technical improvements to current processes.

2. Implement solutions based on an organization’s restrictions, like financial resources, number of users, etc.

<b>Overview</b>: You’ll take what you learned in the System Administration and IT Infrastructure Services course and apply that knowledge to real-world situations.

<b>Assignment</b>: For this writing project, you’ll be presented with three scenarios for different companies. You’ll be doing the systems administration for each company’s IT infrastructure. For each scenario, present improvements to processes based on the company’s needs and current restrictions. There’s no right or wrong answer to your consultation, but your responses should explain the problem, the improvement, and the rationale behind them. Please write a 200-400 word process review for each company presented to you.

### Scenario 1: 

You’re doing systems administration work for Network Funtime Company. Evaluate their current IT infrastructure needs and limitations, then provide at least five process improvements and rationale behind those improvements. Write a 200-400 word process review for this consultation. Remember, there’s no right or wrong answer, but make sure to provide your reasoning.


<b>Software Company</b>:

Network Funtime Company is a small company that builds open-source software. The company is made up software engineers, a few designers, one person in Human Resources (HR), and a small sales team. Altogether, there are 100 employees. They recently hired you as a system administrator to come in and become their IT department.

When a new person is hired on, the HR person purchases a laptop for them to do their work. The HR representative is unfamiliar with what type of hardware is out there; if a new employee requests a laptop, the HR person will purchase the cheapest option for a laptop online. Because of this, almost everyone has a different laptop model. The company doesn’t have too much revenue to spend, so they don’t order laptops until someone gets hired at the company. This leads to a few days of wait time from when someone starts to when they can actually work on a laptop.

The company doesn’t label their computers with anything, so if a computer is missing or stolen, there’s no way to audit it. There’s no inventory system to keep track of what’s currently in the fleet.

Once a computer is purchased, the HR person hands it to the new employee to set up. Software engineers that use Linux have to find a USB drive and add their preferred distribution to the laptop. Anytime someone needs something from HR -- whether it’s office related or tech related -- they email the HR representative directly.

When a new employee gets a machine, they’re given logins to use cloud services. They get a personal orientation with HR to make sure they can login. This requires the HR person to block off a few hours for every new employee. If an employee forgets the login to their machine, they have no way to retrieve a password and they have to reimage their machine. Employees don’t have a strict password requirement to set for their computers.

The company currently has many of their services in the cloud, such as email, word processors, spreadsheet applications, etc. They also use the application, Slack, for instant communication.

## Process Review: Network Funtime Company IT Infrastructure

Network Funtime Company currently operates without a formal IT structure, which has led to inconsistent hardware, inefficient onboarding, and security vulnerabilities. Because HR is solely responsible for purchasing and issuing laptops, employees receive low-performance machines that vary widely in make and model. This inconsistency complicates troubleshooting, device management, and support. Additionally, the lack of asset tags or an inventory management system leaves the company unable to track devices, exposing both financial and security risks. The current onboarding process is also inefficient, relying heavily on HR for ad-hoc device setup, cloud-service login creation, and manual orientation sessions. Password management is another significant issue, with no standard policy and complete device resets required when users forget local credentials.

To address these challenges, I recommend the following improvements:

1. <b>Standardize Hardware Purchases</b>: Select 1–2 approved laptop models for engineers, designers, and sales. This ensures predictable performance, easier support, and bulk-purchase cost savings.

2. <b>Implement an Inventory and Asset Tagging System</b>: Use a lightweight asset platform (e.g., Snipe-IT) and label each device. This creates accountability, supports audits, and reduces loss.

3. <b>Centralize Device Provisioning</b>: IT should image laptops before deployment using standardized OS templates. This reduces setup time and ensures employees have required tools from day one.

4. <b>Adopt a Managed Identity System (e.g., Azure AD or Google Workspace Admin)</b>: Centralized identity management allows for password resets, MFA enforcement, and streamlined onboarding without reimaging devices.

5. <b>Create a Ticketing System for HR and IT Requests</b>: Instead of emailing HR directly, employees should submit requests through a shared helpdesk portal. This improves response visibility, prioritization, and workflow tracking.

Overall, by introducing hardware consistency, security controls, identity management, and process automation, Network Funtime Company can significantly reduce operational overhead while improving employee experience, security, and long-term scalability.