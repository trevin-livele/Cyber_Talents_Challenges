<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/dp.jpg" alt="Logo" width="80" height="80">
  </a>
<h3 align="center">Cyber Talents Challenges by {CyberTrev}</h3>

  <p align="center">
A number of solved challenges on cybertalents platform     <br />
    <a href="https://cybertalents.com/"><strong>Cyber Talents »</strong></a>
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>

  <li>
      <a href="#about-the-project">Introduction to Cybersecurity</a>
      <ul>
        <li><a href="#introduction-to-ctf">introduction to ctf</a></li>
         <li><a href="#introduction-to-web-security">introduction to web security</a></li>
          <li><a href="#html">HTML</a></li>
           <li><a href="#javascript">javascript</a></li> <li><a href="#cookies">Cookies</a></li> <li><a href="#hashing">hashing</a></li> <li><a href="#encoding">encoding</a></li> <li><a href="#obfuscation">obfuscation</a></li> <li><a href="#xss">xss</a></li> <li><a href="#built-with">Directory Traversal</a></li> <li><a href="#built-with">Sensitive Data Exposure</a></li> <li><a href="#built-with">Cyber security Overview</a></li> <li><a href="#built-with">Burpe Suite</a></li> <li><a href="#built-with">Command Injection</a></li>
            <li><a href="#built-with">Code Injection</a></li>
         <li><a href="#built-with">SQL Injection</a></li>
          <li><a href="#built-with">Introduction To Digital Forensics</a></li>
           <li><a href="#built-with">Meta Data</a></li> <li><a href="#built-with">Steganography</a></li> <li><a href="#built-with">Audio Forensics</a></li> <li><a href="#built-with">Wireshark</a></li> <li><a href="#built-with">Netcat</a></li> <li><a href="#built-with">Memory Forensics</a></li> <li><a href="#built-with">Introduction to reverse Engineering</a></li> <li><a href="#built-with">Intel-x86 - Architecture</a></li> <li><a href="#built-with">Introduction to cryptography</a></li> <li><a href="#built-with">Morse code</a></li> <li><a href="#built-with">Ceasar Cipher</a></li>
            <li><a href="#built-with">Hash Cracking</a></li>
      </ul>
    </li>
    
  </ol>

</details>

<!-- ABOUT THE PROJECT -->

## About The Project

 <img src="images/dash.jpeg" alt="Logo" width="720" height="480">

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

<!-- ROADMAP -->

## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
  - [ ] Nested Feature

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Cyber Trev - [@cybertrev](https://twitter.com/cybertrev)

Project Link: [https://github.com/trevin-livele/Cyber_Talents_Challenges](https://github.com/trevin-livele/Cyber_Talents_Challenges)

<p align="right">(<a href="#top">back to top</a>)</p>


## introduction to ctf

<h4>CTF stands for Capture The Flag. This is a type of cybersecurity competition or game with the purpose to locate a particular piece of text called a flag that may be on the server or behind a web page</h4>

````

Introduction to CTF » Pay Me Challenge

flag{ransomeware}

````
<p align="right">(<a href="#top">back to top</a>)</p>

## introduction to web security

I am a cyber security conference that run in August every year in Las Vegas. I am the largest gathering for Hackers in the whole world. No Credit cards, no online booking , Only Cash allowed . Who am I ?

````

Introduction to Web Security » Hackers Gathering 

flag{defcon}

````
<p align="right">(<a href="#top">back to top</a>)</p>

## html

True or False , htmlentities ( convert special characters to its html entity ) can't be exploited to run XSS payload ?

````

HTML » htmlentities 

True

````
<p align="right">(<a href="#top">back to top</a>)</p>

## javascript

1. Enter the website provided in the challenge and you'll be redirected to a login page
2. View the page source of the webpage by right clicking and selecting 'View Page Source'
3. In the source code you'll find a script that is encoded in ascii-hex
4. Decoded this using an online decoder such as this one
After decoding it you would get a simplified code that includes an array with multiple variables followed by an if statement
5. Rearrange the decoded script so it's more readable
After doing so, you'll be able to see that the if statement will redirect you to a page if both the first variable and second variable are equal to the 5th value in the array (Cyber-Talent)
6. Input that in both the username and password of the original webpage and you will be redirected to a page with the flag 
````
JavaScript » This is Sparta 

flag{J4V4_Scr1Pt_1S_Aw3s0me}

````

<p align="right">(<a href="#top">back to top</a>)</p>

## cookies

### What are Cookies?

Cookies are data that browsers store in small text files on your computer.Cookies were invented to solve the problem of "how to remember information about the user?". 
When you sign in to a web application, you won’t need to type your email and password again next time because it stores your credentials in the cookies.


1. Enter the website provided in the challenge and you'll be redirected to a login page.

2. View the page source of the webpage by right clicking and selecting 'View Page Source'.

3. You'll find a comment that includes support username and password.

4. TODO: remove this line , for maintenance purpose use this(user:support password:x34245323)

5. Trying to use these credentials would only redirect you to the support page with no flag.

6. Next you want to open up burp suite and intercept your requests.

7. Try logging back in again with the same credentials but this time with proxy intercept on.

8. You'll find that there is a role variable that is set to support, change that to admin and forward your request.

9. After forwarding your request you should see a new webpage that includes the flag.

````
Cookies » Admin has the power 

flag{hiadminyouhavethepower}
````

<p align="right">(<a href="#top">back to top</a>)</p>

## hashing

Hashing is the process of transforming any given key or a string of characters into another value. This is usually represented by a shorter, fixed-length value or key that represents and makes it easier to find or employ the original string

### Hashing » Hash3rror 

we got this corrupted hash password from a Pcap file with a note (password = sha-1(hash-result)).

```
HASH:77be5d24ed2e3e590045e1d6o7e84i50d2799c19f48ede46804a8734e287df120f
```
Solution: Look at the hash 
```
77be5d24ed2e3e590045e1d6o7e84i50d2799c19f48ede46804a8734e287df120f
```
It's basically in hex format, right? But no, it has two illegal characters: o and i. Let's remove that. Now, it's 64 characters long, which is the length of a sha-256 hash.

We get the plaintext s3cr3tpassword. Now, as per instruction, we've to sha-1 encrypt it. After encryption, we get 

````
flag{83874343435092cb681c0d558a84bfeb389c32ed}
 ````

<p align="right">(<a href="#top">back to top</a>)</p>


## encoding

Encoding is the process of converting a sequence of letters , characters and any other special characters into a specialized format for transmission.Decoding is the reverse of the encoding process


## Encoding » who am i? 

1. Open the challenge && open the source code i.e ```view page source``` or ```inspect element```
2. You get guest Account with Username   ``Guest`` and password as ``Guest``

3. Open Burpe suite to intercept the request
4. input the creds in the browser and forward in burp
5. You get a token decode it as it is base64 encoded.After decoding we get it as ```admin```
6. copy the encoded string replace it in burp and forward to get the flag.

```
flag{B@D_4uTh1Nt1C4T1On}
```
<p align="right">(<a href="#top">back to top</a>)</p>

## obfuscation

What is obfuscation?

Obfuscation is the process of modifying the script to convert it to a difficult,harder-to-understand format, but it will return the same result.

```
Obfuscation » Modify Code 

flag{Obfuscation}

```

Obfuscation » Iam Legend 
If I am a legend, then why am I so lonely?


1. Enter the website provided in the challenge and you'll be redirected to a login page

2. View the page source of the webpage by right clicking and selecting 'View Page Source'

3. You'll find a script that is obfuscated in a weird format doing some research, I found that it was obfuscated using an encoding called jsfuck

4. Going to the original decoder website and using their decoder did not work, as I only got "undefined"

5. I searched for different decoders online and found one called poisonJS that de-obfuscates eval based jsfuck obfuscations after using the decoder, we get multiple functions including the check function for the username and password

6. In the function, we see an if statement that includes the needed variables for the username and password.

```
(user=="Cyber" && pass=="Talent")
```
Entering those credentials will redirect you to a page with the Flag: 
```
flag{J4V4_Scr1Pt_1S_S0_D4MN_FUN}
```
<p align="right">(<a href="#top">back to top</a>)</p>

## xss

Cross-Site Scripting is a web vulnerability that relies on the client side , in which its purpose is to inject HTML (also called HTML injection) or to run JavaScript code in the user’s browser.

XSS » Searching for the cookie 

simple search website we need to know which cookie to eat ;)

#### execute line by line in the input box

```
</script><script>alert(1);</script>

</script><script>alert(document.cookie);</script>

x = try+to+execute+some+jst flag=coolcookie112

flag{coolcookie112}

```
<p align="right">(<a href="#top">back to top</a>)</p>





