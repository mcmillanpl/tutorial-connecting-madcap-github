<?xml version="1.0" encoding="utf-8"?>
<html xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">
    <head>
        <meta name="template" content="Flare.htt" />
    </head>
    <body>
        <h1>Connect a  MadCap project to GitHub</h1>
        <p>This tutorial outlines the steps needed to connect Madcap Flare to GitHub. After connecting your project in GitHub, you will be able to commit all your changes to GitHub and sync the repository with any MadCap Flare project.</p>
        <p>Connecting MadCap Flare to Git can provide several benefits, such as allowing the documentation team to leverage version control, enabling them to track changes, collaborate easily, and roll back to previous versions if needed. Additionally, it streamlines the review and approval process by providing a centralized platform for team members to contribute, comment, and merge changes.</p>
        <h2>&#160;</h2>
        <h2>Prerequisites</h2>
        <p>Before you begin, you will need to have the following:</p>
        <ul>
            <li>
                <p>A GitHub account.</p>
            </li>
            <li>
                <p>Git installed/configured on your local computer.</p>
            </li>
            <li>
                <p>MadCap Flare installed on your computer.</p>
            </li>
            <li>
                <p>A Public and Private key pair generated.</p>
            </li>
            <li>
                <p>Public key tied to your GitHub account.</p>
            </li>
        </ul>
        <h2>&#160;</h2>
        <h2>Connect an existing project to GitHub</h2>
        <ol>
            <li>
                <p>Create a new, empty, repository in GitHub.</p>
            </li>
            <li>
                <p>Copy the HTTP/SSH link that is automatically created with the new repository.</p>
                <p>
                    <img src="../Resources/Images/github-ssh.png" />
                </p>
            </li>
            <li>
                <p>In the existing project in MadCap Flare, select <b>Project</b> from the ribbon and select <b>Project Properties</b>.</p>
            </li>
            <li>
                <p>Open <b>Source Control</b> and select <b>Bind Project</b></p>
                <p>
                    <img src="../Resources/Images/push-on-bind.png" />
                </p>
            </li>
            <li>
                <p>Select Git as the "source control provider" from the drop-down.</p>
            </li>
            <li>
                <p>Select the <b>Remote Repository</b> checkbox to make it true.</p>
            </li>
            <li>
                <p>Optional: <b>If Push on Bind</b> is selected, MadCap will automatically push your MadCap project to GitHub after this process is complete.</p>
            </li>
            <li>
                <p>Paste the HTTP/SSH link you copied into the blank field below <b>Push on bind</b>.</p>
            </li>
            <li>
                <p>Enter your name, email address, then select <b>OK</b>.</p>
            </li>
            <li>
                <p>Review the details of your project in the <b>Project Properties</b> window, then select <b>OK</b>.</p>
                <ul>
                    <li>
                        <p>If you used an SSH URL, you may be prompted to provide your public and private key. Select <b>OK</b> once complete.</p>
                    </li>
                    <li>
                        <p>If you used a HTTP URL, you may be prompted to log-in. Select <b>OK</b> once complete.</p>
                    </li>
                </ul>
            </li>
            <li>
                <p>Refresh the GitHub repository page to see the changes.</p>
            </li>
        </ol>
        <p>The local project has now been uploaded to the empty repository. Changes to your local files in MadCap Flare can be committed and pushed to this new repository.</p>
    </body>
</html>
