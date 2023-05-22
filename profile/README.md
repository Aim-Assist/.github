<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/shreyashkadam/bookify">
    <img src="https://github.com/Ultimate-Coders-Projects/.github/assets/108567267/4228c436-660c-4272-bd5d-6a0afa2ed59f" alt="Logo" width="288">
  </a>

<h3 align="center">AimAssist</h3>

  <p align="center">
    Revolutionize sharpshooting training with our laser-based system, providing safe, accurate, and personalized skill development for defense purposes
    <br />
    <br />
    <a href="https://github.com/Ultimate-Coders-Projects/aimassist-server">AimAssist Server</a>
    .
    <a href="https://github.com/Ultimate-Coders-Projects/aimassist-raspberrypi">AimAssist RaspberryPi</a>
    .
    <a href="https://github.com/Ultimate-Coders-Projects/aimassist-web">AimAssist Web</a>
    .
    <a href="https://github.com/Ultimate-Coders-Projects/aimassit_app">AimAssist App</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About the project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#repositories">Repositories</a></li>
    <li><a href="#problem-statement">Problem Statement</a></li>
    <li><a href="#solution">Solution</a></li>
    <li><a href="#implementation">Implementation</a></li>
    <li><a href="#social-impact">Social Impact</a></li>
    <li><a href="#prototype-images">Prototype Images</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Graphical Representation][product-screenshot]](https://github.com/Ultimate-Coders-Projects/.github/assets/108567267/a31f6439-4568-4577-a08c-aa157a303417)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

<ul>
  <li>
  <a href="https://github.com/Ultimate-Coders-Projects/aimassist-raspberrypi">Hardware</a>
    <ul>
      <li>Raspberry Pi 4</li>
      <li>LDR sensors</li>
      <li>Laser modules</li>
      <li>Breadboards</li>
      <li>I2C LCD Display Module</li>
      <li>Jumper Wires</li>
      <li>HDMI Cable</li>
      <li>Toy Gun</li>
    </ul>
  </li> 
  <li>
    Software
    <ul>
      <li>
        <a href="https://github.com/Ultimate-Coders-Projects/aimassist-server">Server</a>
        <ul>
          <li>Node JS</li>
          <li>MongoDB</li>
          <li>Tensorflow</li>
          <li>Express</li>
          <li>Axios</li>
          <li>numjs</li>
        </ul>
      </li>
      <li>
        <a href="https://github.com/Ultimate-Coders-Projects/aimassist-web">Web Frontend</a>
        <ul>
          <li>React JS</li>
          <li>Next JS file routing</li>
          <li>Firebase Google Authentication</li>
          <li>Material UI</li>
          <li>Formik</li>
          <li>Simplebar</li>
          <li>MUI Icons</li>
          <li>date-fns</li>
          <li>dayjs</li>
        </ul>
      </li>
      <li>
        <a href="https://github.com/Ultimate-Coders-Projects/aimassit_app">Mobile Application</a>
        <ul>
          <li>Flutter</li>
          <li>Firebase</li>
          <li>Flutter Charts</li>
          <li>JWT</li>
        </ul>
      </li>
    </ul>
  </li> 
</ul>


## Repositories

  <ul>
    <li>
      <a href="https://github.com/Ultimate-Coders-Projects/aimassist-server">AimAssist Server</a>
    </li>
    <li>
      <a href="https://github.com/Ultimate-Coders-Projects/aimassist-raspberrypi">AimAssist RaspberryPi</a>
    </li>
    <li>
      <a href="https://github.com/Ultimate-Coders-Projects/aimassist-web">AimAssist Web</a>
    </li>
    <li>
      <a href="https://github.com/Ultimate-Coders-Projects/aimassit_app">AimAssist App</a>
    </li>
  <ul>


## Problem Statement
The lack of safe and accessible training methods for sharpshooting skills poses a challenge for military and law enforcement personnel, as well as civilian firearms enthusiasts. Traditional training methods require expensive ammunition and range time, making it difficult for individuals to maintain their skills on a regular basis. Additionally, these methods often provide limited feedback and may not accurately simulate real-world scenarios.

To address these challenges, there is a need for an innovative and safe training method that utilizes advanced technology to provide realistic simulation and accurate feedback. Such a system would allow users to train regularly and efficiently, without the need for expensive ammunition or range time. Additionally, this system could provide personalized feedback and training programs to help users improve their skills and accuracy.

## Solution
Our cutting-edge laser-based system provides a safe and innovative solution for sharpshooting training. The system features a circular target with varying radius levels, each inscribed with LDR sensors that measure a shooters precision and accuracy. The LDRs on each radius level have the same points, ranging from 1-5, in decreasing order from the center of the target to the outer edge.All data generated by the system, including distance, angle, and points scored, is sent to a central server and analyzed using advanced machine learning algorithms. This analysis provides valuable insights into a shooters performance, identifying areas of strength and areas for improvement. By leveraging the power of machine learning, users can receive personalized feedback and tailored training programs designed to enhance their sharpshooting skills and maximize their effectiveness in the field.With particular relevance to defense purposes, our system offers a safe and effective way for military and law enforcement personnel to train their shooting skills without the need for live ammunition or putting themselves or others at risk. Our laser-based system represents a major leap forward in the pursuit of precision and accuracy in defense training, making it an essential tool for anyone looking to enhance their sharpshooting skills.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Implementation
Our team has a wealth of experience in implementing the proposed idea on the ground. We have successfully developed a functional prototype that demonstrates the core principles of the system.
<br>
To begin with, we have designed the system to utilize laser technology instead of traditional bullets. The laser is securely attached to the gun, enabling precise targeting of the designated region. This ensures a safer and more cost-effective approach to sharpshooting training.
<br>
The target region itself is a circular disc that comprises various concentric circles, each with a distinct radius. At every level of radius, we have strategically placed Light Dependent Resistors (LDRs). These LDRs are responsible for capturing the laser hits and determining the scores. Remarkably, all the LDRs positioned at the same level of radius yield identical points. The scoring system follows a scale of 1 to 5, with points decreasing as one moves away from the center of the target towards the outer edges.
<br>
To capture and process the scoring data, we have developed a comprehensive infrastructure. A crucial component of our system is a web application built using Next.js and the MERN (MongoDB, Express.js, React.js, Node.js) stack. This web application allows users to conveniently access their training data, review their performance, and initiate training sessions. Additionally, we have designed a mobile application using Flutter, providing users with the flexibility to view their scores and track their progress on the go.
<br>
To enhance the system's capabilities, we have employed machine learning techniques. By leveraging TensorFlow on the server side, we are able to manipulate the collected data and extract valuable insights regarding the user's accuracy and performance. This allows us to generate personalized feedback and recommendations to help individuals improve their sharpshooting skills effectively.
<br>
For data storage, we have opted for the robust and scalable MongoDB database. This enables us to securely store the scoring data and training records, ensuring easy access and retrieval whenever required.
<br>
Overall, our team has made significant progress in implementing this idea on-ground. With our functional prototype, comprehensive web and mobile applications, and the integration of machine learning using TensorFlow, we are well-equipped to deliver a sophisticated training system that can be immensely valuable, particularly in defense applications.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Social Impact
The anticipated social impact of our laser-based sharpshooting training system is significant. It can reduce the risk of accidents and injuries associated with traditional sharpshooting training methods, democratize access to training, and improve the accuracy of military, law enforcement personnel, and civilian shooters. Our system can have positive implications for public safety, particularly in law enforcement where accurate shooting skills are critical to ensuring officer and public safety.

## Protoype Images

<!-- CONTACT -->

## Contact

Shreyash Kadam - [@linkedin-handle](https://linkedin.com/in/shreyash-kadam) - shreyash.kadam10@gmail.com

Project Link: [https://github.com/shreyashkadam/bookify](https://github.com/shreyashkadam/bookify)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/shreyashkadam/bookify.svg?style=for-the-badge
[contributors-url]: https://github.com/shreyashkadam/bookify/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/shreyashkadam/bookify.svg?style=for-the-badge
[forks-url]: https://github.com/shreyashkadam/bookify/network/members
[stars-shield]: https://img.shields.io/github/stars/shreyashkadam/bookify.svg?style=for-the-badge
[stars-url]: https://github.com/shreyashkadam/bookify/stargazers
[issues-shield]: https://img.shields.io/github/issues/shreyashkadam/bookify.svg?style=for-the-badge
[issues-url]: https://github.com/shreyashkadam/bookify/issues
[license-shield]: https://img.shields.io/github/license/shreyashkadam/bookify.svg?style=for-the-badge
[license-url]: https://github.com/shreyashkadam/bookify/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/shreyash-kadam
[product-screenshot]: https://github.com/Ultimate-Coders-Projects/.github/assets/108567267/a31f6439-4568-4577-a08c-aa157a303417
[product-screenshot1]: readme-images/screenshot1.png
[product-screenshot2]: readme-images/screenshot2.png
[product-screenshot3]: readme-images/screenshot3.png
[product-screenshot4]: readme-images/screenshot4.png
[product-screenshot5]: readme-images/screenshot5.png
[product-screenshot6]: readme-images/screenshot6.png
[product-screenshot7]: readme-images/screenshot7.png
[product-screenshot8]: readme-images/screenshot8.png
[product-screenshot9]: readme-images/screenshot9.png
