# MS-Security-Copilot---Explore-file-uploads-as-a-knowledge-base
In this exercise, you go through the process of integrating a knowledge base into copilot, using file upload and then you do some basic testing with prompts that pull information from that knowledge base.


**Before you start**

For this exercise, you'll be using a sample file, '**Woodgrove Corporate Data Handling Policy.pdf**.'

Select the link Woodgrove Corporate Data Handling Policy.pdf' to access the sample file. https://github.com/MicrosoftLearning/SC-5006-Get-started-with-Microsoft-Copilot-for-Security/blob/master/Sample%20files/Woodgrove%20Corporate%20Data%20Handling%20Policy.pdf

Select the Download raw file download raw file icon icon. Save the file on your local computer, as you'll need it later.

Alternatively, because this is a simulation, you can create the file named 'Woodgrove Corporate Data Handling Policy.pdf.' Because this is a simulation, the contents of the file you create won't matter. The prompt responses shown in the simulation, however, are based on the actual file.

**Task 1: Configure Copilot to support file uploads**

In this task, you start by attempting a file upload but realize that there's no way to actually upload a file. This is an indication that the file upload option isn't configured. As a user with the Copilot owner role, you enable file uploads and then test using a file as a knowledge base for Copilot.

Open the simulated environment by selecting this link: Microsoft Security Copilot. https://7lraebk5le-0de6q8m2yh.app.highlights.guide/

To access file uploads, select the sources icon sources icon from the prompt bar.

From the manage sources page, select Files.

If there's no option to actually upload a file, it's because the owner setting that controls this option has been changed from the default. After conferring with the other Copilot owner, you realize this was disabled in error and agree this should be set.

Close the manage source window by selecting the X on the top right corner of the window.

Select the Home menu icon (hamburger icon).
Select Owner settings.
Scroll-down to Files. Select the drop-down and set it to Contributors and owners can upload files.
Return to the landing page. Select Microsoft Security Copilot next to the home menu (hamburger) icon.

**Task 2: Upload a file and run test prompts**

In this task, you upload a file and proceed to run prompts that use that file.

From the landing page, select the Sources icon located in the promptbar.

From the Manage Sources page, select Files.

Select Upload file. Upload the file Woodgrove Corporate Data Handling Policy.pdf that you previously downloaded or created. Once the file is uploaded, close the manage sources window.

With the files uploaded, you can now try some prompts. In the prompt bar, you need to mention "uploaded files" if you want Copilot to reason over your available files. You can also include the file name if you would like to guide Copilot to reason over a specific file. Enter the following prompts. You can use copy/paste:

**Prompt:** Summarize the uploaded file Woodgrove Corporate Data Handling Policy.pdf. The process log shows that Copilot chose file uploads and successfully processed the prompt.

**Prompt:** Based on the uploaded file Woodgrove Corporate Data Handling Policy.pdf what data handling policies should I consider implementing in Microsoft Purview. The process log shows that Copilot chose Microsoft Purview. The prompt response demonstrates the power of Copilot. Copilot maintains the context of the previous prompt response and integrates that information with the capability of Microsoft Purview. Although not shown in this exercise, Copilot can reason across multiple files.

**Review**

In this task, you configured to allow contributors and owners to upload files, you uploaded a file, and tested prompts that reasoned over the uploaded file.
