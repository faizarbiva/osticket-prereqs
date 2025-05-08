<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Explanation</h1>
This project lists the prerequisites required to install the open-source help desk ticketing system osTicket. It also explains why some of the selected pre-reqs need to be installed as well as the importance.<br />


<h2>Environments and Technologies Used</h2\>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- OsTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>To install and run osTicket successfully, a few system requirements must be met so heres a list of some of the Prerequisites.</h2>

- VC_redist.x86.exe.
- MYSQL 5.5.62
- rewrite_amd64_en-US.msi
- PHPManagerForIIS_V1.5.0.msi
- HeidiSQL

<h2>Explanation and importance</h2>



![os-mysequel](https://github.com/user-attachments/assets/42b70f92-6f7c-4102-a8d3-aff1b466b4da)
MySQL is a free tool that helps you store and organize data for websites and apps. It's important to install because it lets you build and test projects on your own computer. With MySQL, you can handle things like login systems, user info, and content. It's a key part of making any app that needs to work with data smoothly and securely. 



![osticket-mysequel](https://github.com/user-attachments/assets/d66471f9-7045-4ebc-98ae-a9c4b7d24edc)
During MySQL setup, there's a step where you're asked to set a root password - this is super important. The root user has full access to the database, so choosing a strong password helps keep everything secure. It’s basically locking the door to your data, making sure only you can make big changes. It’s important to pick a strong one because this account has full control over everything. If you use a weak password, it’s easier for someone to break in and mess with your data, delete stuff, or even steal information. So setting a secure password is just a smart way to protect your work from any unwanted surprises.



![osticket rewrite mod](https://github.com/user-attachments/assets/b15dd075-2fc7-44c1-b946-e1c5af260e66)
You need to install the IIS URL Rewrite Module 2 setup wizard when setting up osTicket on IIS because it enables the system to handle clean URLs and route requests properly. OsTicket relies on URL rewriting to direct traffic between the users. So, Without the rewrite module, IIS won’t know how to handle these routes, and you’ll likely run into broken links and 404 errors. Installing the rewrite module ensures everything runs smoothly and the system can route requests the right way—making it a crucial step in the setup.


