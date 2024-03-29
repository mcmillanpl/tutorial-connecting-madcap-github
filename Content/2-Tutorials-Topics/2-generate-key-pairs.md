<?xml version="1.0" encoding="utf-8"?>
<html xmlns:MadCap="http://www.madcapsoftware.com/Schemas/MadCap.xsd">
    <head>
    </head>
    <body>
        <h1>Generate a private and public key pair</h1>
        <p>A private/public key pair is necessary to connect MadCap Flare with a Git repository. This tutorial walks you through the process of generating a private/public key pair using Git Bash. If you are using Linux/macOS, you will need to follow a different process.</p>
        <h2>&#160;</h2>
        <h2>Check for existing key pairs</h2>
        <p>Before generating a key pair, you should check to make sure you don't already have one:</p>
        <p>Open Git Bash</p>
        <ol>
            <li>
                <p style="font-weight: bold;"><span style="font-weight: normal;">Paste </span><code style="font-weight: normal;">cd ~/.ssh</code> <span style="font-weight: normal;">and press</span> Enter. </p>
            </li>
            <li>
                <p style="font-weight: normal;"><span style="font-weight: normal;">Paste </span><code>ls</code> and press <b>Enter</b>.</p>
            </li>
        </ol>
        <p>If you have keys, they will be listed as files with names similar to: <code>id_dsa</code> or <code>id_ed25519</code> (this will be your private key), as well as a matching file with a <code>.pub</code> extension (this is the public key).</p>
        <p>If these files do not appear, then you will need to generate keys. </p>
        <h2>&#160;</h2>
        <h2>Generate a private/public key pair</h2>
        <ol>
            <li>
                <p>Paste <code>ssh-keygen -o</code> and press <b>Enter</b>.</p>
            </li>
            <li>
                <p>When prompted to enter a file in which to save the key, you can press <b>Enter</b> to accept the default. </p>
            </li>
            <li>
                <p>Create a passphrase when prompted or press <b>Enter</b> twice to skip.</p>
            </li>
            <li>
                <p>Your keys will be generated and saved in the appropriate folder (<code>(/home/USERNAME/.ssh/id_rsa)</code> is the default).</p>
            </li>
        </ol>
        <p>&#160;</p>
    </body>
</html>
