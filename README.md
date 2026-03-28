# MADCAP 

## Overview 

MadCap is a coffee app where users on the go can order various drinks and snacks on their device.

## Features 
Browse throughout the coffee menu items 
Customize orders 
Search functionality 
Secure checkout 
Clear and clean visuals 

## Timeline 
4 weeks 

## Framework
SwiftUI
Internal Combine

## Development Journey 

During this challenge, I was introduced to more concepts that deepened my understanding of coding. After being introduced to Enums, Functions, and Segmented Pickers, I was developing at a higher level. 

This project gave me the confidence to push forward in my coding journey. I was able to recognize and build repetition by coding some things that I learned from my last project. Now I’m familiar with coding concepts such as Arrays, HStacks, VStacks, and Buttons.

The main challenge I faced was understanding how data flowed between views. Other challenges I faced were coding functions to calculate the total for drinks, how I named and organized my work. I overcame these problems by asking questions, using resources, and implementing what I learned in my project. I became better at writing logic, naming properties, and data flow. My project includes a menu view where users pick a drink of their choice, customization page, and an order confirmation view.

## Technical Walkthrough

<img width="200" height="380" alt="Screenshot 2026-03-28 at 4 20 35 AM" src="https://github.com/user-attachments/assets/4380353b-e81c-4860-90bf-c4ce165a7487" />

<img width="200" height="400" alt="Screenshot 2026-03-28 at 4 21 05 AM" src="https://github.com/user-attachments/assets/75202071-59f5-461a-a7d1-549ef555b960" />

For this app, I developed a feature that allows users to customize their drink by selecting different milk and sugar options. 

<img width="558" height="461" alt="Screenshot 2026-03-28 at 4 18 28 AM" src="https://github.com/user-attachments/assets/f43f2584-0753-4ad2-abed-b9da232416fd" />

First, I created two enums called Milk and Sugar, and specified the available options for each enum.


<img width="600" height="600" alt="Screenshot 2026-03-28 at 4 20 52 AM" src="https://github.com/user-attachments/assets/cd286afa-c946-476d-8a7b-b53f31fe80c1"
  />

I then added the segmented picker with placement modifiers and ForEach to iterate through the enum cases to display the options 
  
<img width="600" height="600" alt="Screenshot 2026-03-28 at 4 21 26 AM" src="https://github.com/user-attachments/assets/23d2ea8f-5921-48ee-bd98-41fb40aed435" />

Finally, I utilized String interpolation to display the selected option made by the user.
