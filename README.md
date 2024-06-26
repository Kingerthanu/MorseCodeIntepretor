# CPP_MorseCodeIntepretor

  Project In Which Uses Audio Output On System To Listen For Morse Code Coming In And Interpreting It Into Its English Interpretation. Also Uses User Input To Translate It Into Morse Code And Output The Noise In Morse Code At A Given Pitch For A Dynamic Length Of Time, Following The Morse-Code Standards For Time-Units.

----------------------------------------------

<img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/88a0641b-10e0-4891-9a69-27d0c58fc038" alt="Cornstarch <3" width="65" height="49"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/88a0641b-10e0-4891-9a69-27d0c58fc038" alt="Cornstarch <3" width="65" height="49"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/88a0641b-10e0-4891-9a69-27d0c58fc038" alt="Cornstarch <3" width="65" height="49"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/88a0641b-10e0-4891-9a69-27d0c58fc038" alt="Cornstarch <3" width="65" height="49"> 


**The Breakdown:**

This Program Works With The Terminal And Users Input To Convert A Message Into Morse Code, Emit The Sound Of Their String And With Windows Audio Output Detect The Morse And Reconvert It Into A Message.

The Program Deepdown Is Working On 3 Stages:

  - 1.) Translation To Of User Input Into Morse<br>
  - 2.) Emittion Of User Morse On PC<br>
  - 3.) Catching Of User Morse On PC<br>

The Program Starts By Asking The User For Their Given Strictly-Alphabetic String Input In Which They Want To Convert To Morse Code. After Hitting Enter, This Input Will Be Converted Into Morse Code Using **-** For A Long Beep & **.** For A Short Beep. The Program Works Off The International Standards For Morse Code With Spaces Between Words Being 6 Instead Of 7 Units. After The Input Is Converted, The Program Will Create A Detached Thread In Which Will Use A Audio Output Listening Algorithm In Order To Listen To The Computer For Incoming Morse Code Inputs. It Will Detect This Morse, And Using Lengths Of The Given Sounds To Interpolate What Type Of Character Is Being Communicated, Like A **' '**, **'-'**, or **'.'**. After Receiving A Given Character--Denoted By A Single 3-Unit Wait--It Will Interpret The Given Morse Letter Back Into English. The Listening Thread Will Keep Listening For Morse Even After The Sounding Thread Has Concluded And Can Be Terminated With CTRL + C.

If You Know The Tempo Of A Current Morse Code Transaction You Can Run The Listening Thread Alone By Itself And Will Still Listen For The Passed Morse Asynchronously. The Listening Thread Also Works On 2 Stages Instead Of The Three Of Our Main Sounding Thread As We Only Have The 2 Stages Of:

  - 1.) Catching Of User Morse On PC<br>
  - 2.) Translation To Of User's Morse Input Into English<br>

Currently It Works Reliably With The Morse Being The Only Sound Picked Up By The System And Has Difficulties With Inconsistent Samples But Will Swap Out Buffer Sampling Algorithm To Something More Reliable.

<img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/739a779e-c28a-43d7-9d7c-9576a12beae8" alt="Cornstarch <3" width="65" height="49"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/739a779e-c28a-43d7-9d7c-9576a12beae8" alt="Cornstarch <3" width="65" height="49"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/739a779e-c28a-43d7-9d7c-9576a12beae8" alt="Cornstarch <3" width="65" height="49"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/739a779e-c28a-43d7-9d7c-9576a12beae8" alt="Cornstarch <3" width="65" height="49">

----------------------------------------------

<img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/ae006dac-e413-475a-8523-f48f0068144b" alt="Cornstarch <3" width="65" height="49"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/ae006dac-e413-475a-8523-f48f0068144b" alt="Cornstarch <3" width="65" height="49"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/ae006dac-e413-475a-8523-f48f0068144b" alt="Cornstarch <3" width="65" height="49"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/ae006dac-e413-475a-8523-f48f0068144b" alt="Cornstarch <3" width="65" height="49"> 


**Features:**

![ohioClient-ezgif com-video-to-gif-converter](https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/a08fe215-d361-4a11-8b37-35290daaf6af)

![2024-06-1518-06-19-ezgif com-video-to-gif-converter](https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/72d24711-eaa1-4c5d-9ecf-e7a49dc0d563)


<img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/3cb63ad6-2fc7-4b4b-9fa8-142e78124d24" alt="Cornstarch <3" width="75" height="59"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/3cb63ad6-2fc7-4b4b-9fa8-142e78124d24" alt="Cornstarch <3" width="75" height="59"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/3cb63ad6-2fc7-4b4b-9fa8-142e78124d24" alt="Cornstarch <3" width="75" height="59"> <img src="https://github.com/Kingerthanu/CPP_MorseCodeIntepretor/assets/76754592/3cb63ad6-2fc7-4b4b-9fa8-142e78124d24" alt="Cornstarch <3" width="75" height="59">
