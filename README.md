# Testing

Learn about various software testing methodologies and why it is important to test your code.
- [Wikipedia - Software testing](https://en.wikipedia.org/wiki/Software_testing)
- [Software Testing Methodologies](https://smartbear.com/learn/automated-testing/software-testing-methodologies/)
- [Learn The Methods & Tools](https://www.inflectra.com/ideas/topic/testing-methodologies.aspx)
- [Testing Automation University](https://testautomationu.applitools.com/)

## How does software testing work?

> Software testing is the process of evaluating and verifying that a software product or application does what it is supposed to do. The benefits of testing include preventing bugs, reducing development costs and improving performance. 

## Types of software testing

There are many different types of software tests, each with specific objectives and strategies:

- **Acceptance testing**: Verifying whether the whole system works as intended.
- **Integration testing**: Ensuring that software components or functions operate together.
- **Unit testing**: Validating that each software unit performs as expected. A unit is the smallest testable component of an application.
- **Functional testing**: Checking functions by emulating business scenarios, based on functional requirements. Black-box testing is a common way to verify functions.
- **Performance testing**: Testing how the software performs under different workloads. Load testing, for example, is used to evaluate performance under real-life load conditions.
- **Regression testing**: Checking whether new features break or degrade functionality. Sanity testing can be used to verify menus, functions and commands at the surface level, when there is no time for a full regression test.
- **Stress testing**: Testing how much strain the system can take before it fails. Considered to be a type of non-functional testing.
- **Usability testing**: Validating how well a customer can use a system or web application to complete a task.

In each case, validating base requirements is a critical assessment. Just as important, exploratory testing helps a tester or testing team uncover hard-to-predict scenarios and situations that can lead to software errors.

Even a simple application can be subject to a large number and variety of tests. A test management plan helps to prioritize which types of testing provide the most value – given available time and resources. Testing effectiveness is optimized by running the fewest number of tests to find the largest number of defects.

## History of software testing

> Software testing arrived alongside the development of software, which had its beginnings just after the second world war. Computer scientist Tom Kilburn is credited with writing the first piece of software, which debuted on June 21, 1948, at the University of Manchester in England. It performed mathematical calculations using machine code instructions.

Debugging was the main testing method at the time and remained so for the next two decades. By the 1980s, development teams looked beyond isolating and fixing software bugs to testing applications in real-world settings. It set the stage for a broader view of testing, which encompassed a quality assurance process that was part of the software development life cycle.

“In the 1990s, there was a transition from testing to a more comprehensive process called quality assurance, which covers the entire software development cycle and affects the processes of planning, design, creation and execution of test cases, support for existing test cases and test environments,” says Alexander Yaroshko in his post on the uTest developer site.

“Testing had reached a qualitatively new level, which led to the further development of methodologies, the emergence of powerful tools for managing the testing process and test automation tools.”

## Continuous testing

Software testing has traditionally been separated from the rest of development. It is often conducted later in the software development life cycle after the product build or execution stage. A tester may only have a small window to test the code – sometimes just before the application goes to market. If defects are found, there may be little time for recoding or retesting. It is not uncommon to release software on time, but with bugs and fixes needed. Or a testing team may fix errors but miss a release date.

Doing test activities earlier in the cycle helps keep the testing effort at the forefront rather than as an afterthought to development. Earlier software tests also mean that defects are less expensive to resolve.

Many development teams now use a methodology known as continuous testing. It is part of a DevOps approach – where development and operations collaborate over the entire product life cycle. The aim is to accelerate software delivery while balancing cost, quality and risk. With this testing technique, teams don’t need to wait for the software to be built before testing starts. They can run tests much earlier in the cycle to discover defects sooner, when they are easier to fix.

## Why software testing is important

>Few can argue against the need for quality control when developing software. Late delivery or software defects can damage a brand’s reputation — leading to frustrated and lost customers. In extreme cases, a bug or defect can degrade interconnected systems or cause serious malfunctions.

Consider Nissan having to recall over 1 million cars due to a software defect in the airbag sensor detectors. Or a software bug that caused the failure of a USD 1.2 billion military satellite launch. The numbers speak for themselves. Software failures in the US cost the economy USD 1.1 trillion in assets in 2016. What’s more, they impacted 4.4 billion customers.

Though testing itself costs money, companies can save millions per year in development and support if they have a good testing technique and QA processes in place. Early software testing uncovers problems before a product goes to market. The sooner development teams receive test feedback, the sooner they can address issues such as:

- Architectural flaws
- Poor design decisions
- Invalid or incorrect functionality
- Security vulnerabilities
- Scalability issues

When development leaves ample room for testing, it improves software reliability and high-quality applications are delivered with few errors. A system that meets or even exceeds customer expectations leads to potentially more sales and greater market share.

## Software testing best practices

>Software testing follows a common process. Tasks or steps include defining the test environment, developing test cases, writing scripts, analyzing test results and submitting defect reports.

Testing can be time-consuming. Manual testing or ad-hoc testing may be enough for small builds. However, for larger systems, tools are frequently used to automate tasks. Automated testing helps teams implement different scenarios, test differentiators (such as moving components into a cloud environment), and quickly get feedback on what works and what doesn't.

A good testing approach encompasses the application programming interface (API), user interface and system levels. As well, the more tests that are automated, and run early, the better. Some teams build in-house test automation tools. However, vendor solutions offer features that can streamline key test management tasks such as:

- **Continuous testing**: Project teams test each build as it becomes available. This type of software testing relies on test automation that is integrated with the deployment process. It enables software to be validated in realistic test environments earlier in the process – improving design and reducing risks.

- **Configuration management**: Organizations centrally maintain test assets and track what software builds to test. Teams gain access to assets such as code, requirements, design documents, models, test scripts and test results. Good systems include user authentication and audit trails to help teams meet compliance requirements with minimal administrative effort.

- **Service virtualization**: Testing environments may not be available, especially early in code development. Service virtualization simulates the services and systems that are missing or not yet completed, enabling teams to reduce dependencies and test sooner. They can reuse, deploy and change a configuration to test different scenarios without having to modify the original environment.

- **Defect or bug tracking**: Monitoring defects is important to both testing and development teams for measuring and improving quality. Automated tools allow teams to track defects, measure their scope and impact, and uncover related issues.

- **Metrics and reporting**: Reporting and analytics enable team members to share status, goals and test results. Advanced tools integrate project metrics and present results in a dashboard. Teams quickly see the overall health of a project and can monitor relationships between test, development and other project elements.

[**_Next section_**](./Test_Plan/README.md)