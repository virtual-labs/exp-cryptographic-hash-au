### Procedure
<h5>Hashing</h5>
<p> click on the hashing button and enter the message  you want to get hashed </p>

<p>Select the algorithm with which you need to hash the message, such as MD5 or SHA-256. </p>
<img src="./images/step1.png">
<p>Hashed input value is displayed </p>


<h5>Preimage</h5>
<p> click on the Preimage button ,Select the algorithm with which you need to hash the message </p>
<img src="./images/step2.png">
<p>Click the "Generate Hash" button to view the hash value generated for the hidden input. </p>
<img src="./images/step2.1.png">
<p>Step 2: Try to guess the hidden input and click the "Submit" button to check if the hash values match.
<img src="./images/step2.3.png">
<p> If the generated hash is the same as the previous one, the input has been successfully cracked. However, if the hash values differ, it demonstrates preimage resistance, meaning it is computationally difficult to determine the original input from its hash. </p>
<img src="./images/step2.4.png">

<h5>SecondPreimage</h5>
<p> Click the "Second Preimage" button, select an algorithm (MD5, SHA-256, or SHA-512), and view the generated hash value.</p>
<img src="./images/step3.png">

<P> Step 2: Find a Different Input with Same Hash</P>
<img src="./images/step3.1.png">
<p>If the generated hash does not match the previous hash, it demonstrates strong second preimage resistance! Even with knowledge of the original hash, finding another input that produces the same hash is computationally infeasible, ensuring security.</p>




<h5>Collision Resistance</h5>
<p>clicks on the "Collision Resistance" button and select an algorithm (MD5, SHA-256, or SHA-512)</p>
<img src="./images/step4.png">
<p>Enter the unknown first message, or click the "Random" button to generate a message automatically. The corresponding hash value will be displayed </p>
<img src="./images/step4.1.png">
<p>Enter the unknown second message, or click the "Random" button to generate a message automatically. The corresponding hash value will be displayed 
<img src="./images/step4.2.png">
<p>Click the "Check for Collision" button to compare the hash values of two unknown inputs. If the hashes are different, it confirms collision resistance, meaning it is difficult to find two different inputs that produce the same hash. </p>
<img src="./images/step4.3.png">