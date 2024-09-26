# Interview Transcript: z/OS Management Facility Usage in a Large European Insurance Provider

**Interviewer (I):** Thank you for taking the time to speak with me today. Could you start by telling me about your role and experience in the insurance industry, particularly with z/OS Management Facility?

**Respondent (R):** Of course. I've been with this insurance company for 25 years now. I started as a mainframe operator and worked my way up to my current position as the Lead Mainframe Systems Architect. I've been using z/OS Management Facility, or z/OSMF, since it was first introduced, so that's about 10 years now.

**I:** That's quite a wealth of experience. How has z/OSMF changed your work over the years?

**R:** It's been quite a journey. When I started, everything was done manually through TSO/ISPF. The introduction of z/OSMF was a significant shift. Initially, there was some resistance – you know how it is with change – but over time, it's become an indispensable tool for us.

**I:** Could you elaborate on how you use z/OSMF for software installation and configuration in your insurance environment?

**R:** Certainly. In the insurance industry, we deal with a lot of sensitive customer data and complex actuarial calculations. Our mainframe runs critical applications for policy management, claims processing, and risk assessment. We use z/OSMF primarily for managing the software that supports these functions.

For installation, we rely heavily on the Software Management task in z/OSMF. It allows us to manage the entire software lifecycle, from acquisition to deployment and maintenance.

**I:** Can you walk me through a typical installation process?

**R:** Sure. Let's say we're updating our claims processing software. First, I'll create a new deployment in z/OSMF. This deployment includes all the details about the software package, where it's coming from, and where it needs to be installed.

One of the things I appreciate about z/OSMF is its ability to handle our complex system landscape. We have separate LPARs for different lines of business – life insurance, property and casualty, reinsurance, and so on. z/OSMF allows me to specify which LPARs need the update and in what order.

**I:** That sounds complex. How do you ensure consistency across these different environments?

**R:** That's where z/OSMF really shines. We've created a series of standardized workflows for different types of installations and updates. These workflows include not just the basic installation steps, but also our company-specific configuration requirements, security checks, and testing procedures.

For example, after installing an update to our claims processing software, we need to run a series of data integrity checks and update some parameters in our fraud detection system. All of this is built into our z/OSMF workflow.

**I:** How does z/OSMF help you meet the regulatory requirements specific to the European insurance industry?

**R:** That's a crucial point. As you know, the insurance industry in Europe is heavily regulated, with requirements like Solvency II and GDPR. z/OSMF helps us in several ways:

First, its robust logging and reporting features provide the audit trail we need. We can show regulators exactly what changes were made to our systems, when, and by whom.

Second, we've incorporated regulatory checks into our z/OSMF workflows. For example, before any software update that might affect our risk calculations, we have mandatory steps to verify compliance with Solvency II requirements.

Lastly, z/OSMF's role-based security aligns well with GDPR requirements. We can ensure that only authorized personnel have access to systems containing personal data.

**I:** That's interesting. Have you faced any challenges using z/OSMF in your insurance environment?

**R:** Yes, we've had our share of challenges. One of the biggest was integrating z/OSMF with our legacy systems. Some of our insurance products have been around for decades, and we still maintain some very old applications. Making these work smoothly with z/OSMF required some creative solutions.

Another challenge was performance. Insurance calculations, especially for long-term life insurance products, can be very compute-intensive. We had to carefully optimize our z/OSMF workflows to ensure that software updates and configuration changes didn't impact our ability to run these critical calculations.

**I:** How did you address these challenges?

**R:** For the legacy systems, we developed a series of custom scripts that act as a bridge between z/OSMF and our older applications. It's not elegant, but it works.

As for performance, we've set up dedicated maintenance windows and use z/OSMF's capability to schedule jobs to ensure that our heavy-duty actuarial runs aren't impacted. We also worked closely with our IBM representatives to optimize our z/OSMF configuration for our specific workload.

**I:** Looking back over your 25 years in the industry, how has z/OSMF impacted mainframe management in insurance?

**R:** It's been transformative. The insurance industry has always been data-intensive, but the volume and complexity of data we handle now is orders of magnitude greater than when I started. Without tools like z/OSMF, managing our mainframe environment would be incredibly challenging.

z/OSMF has allowed us to be more agile in responding to market changes and new regulations. We can roll out updates faster and with more confidence. It's also helped us address the skills gap – as many of my experienced colleagues retire, z/OSMF's intuitive interface makes it easier to train new team members.

That said, I always stress to my team that z/OSMF is a tool, not a replacement for understanding the underlying mainframe technologies. In insurance, where precision and reliability are paramount, that deep knowledge is still crucial.

**I:** Thank you so much for sharing your experiences and insights. This has been very informative.

**R:** You're welcome. It's always a pleasure to discuss how technology has evolved in our industry. If you have any more questions, feel free to ask.

