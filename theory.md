## Theory


<p>Hash functions play a crucial role in various security applications, including password storage (hash values instead of passwords), digital signatures, and data integrity checks. Hash values, or message digests, are values that a hash function returns. The hash function is shown in the image below −</p>
<img src="./images/hahsing.png" alt="alternative_text" width="width_value" height="height_value">

<h4>Properties of hash functions</h4>

<p>Pre-Image Resistance</p>
 <p>
        A cryptographic hash function <b>h</b> is preimage resistant if it is 
        <b>computationally infeasible</b> to determine the original input <b>x</b> 
        given only the hash output <b>h(x)</b>. This means that even if <b>h(x)</b> is known, 
        finding an <b>x</b> such that <b>h(x)</b> produces the given output is extremely difficult.
    </p>
<img src="./images/prehash.jpg" alt="alternative_text" style="display: block; margin: auto;">


<h4>Second Pre-Image Resistance</h4>
 <p>
        A cryptographic hash function <b>h</b> satisfies <b>second preimage resistance</b> if:
    </p>
    
 <ul>
        <li>Given an input <b>x₁</b> and its hash <b>h(x₁)</b>, it should be <b>computationally infeasible</b> to find another input <b>x₂</b> such that <b>h(x₁) = h(x₂)</b>.</li>
        <li>In other words, an attacker should not be able to find a different input <b>x₂</b> that produces the same hash as <b>x₁</b>.</li>
        <li>This property ensures the integrity of digital signatures and stored passwords by preventing intentional collisions.</li>
        <li>Second preimage resistance is crucial in preventing forgery and tampering with hashed data.</li>
</ul>
<img src="./images/secondhash.jpg" alt="alternative_text" width="width_value" height="height_value" style="display: block; margin: auto;">

<h4>Collision Resistance</h4>
  <p>
        A cryptographic hash function <b>h</b> satisfies <b>collision resistance</b> if:
    </p>
    
<ul>
        <li>It is <b>computationally infeasible</b> to find two different inputs <b>x₁</b> and <b>x₂</b> such that <b>h(x₁) = h(x₂)</b>.</li>
        <li>In other words, no two distinct inputs should produce the same hash value.</li>
        <li>This property ensures the security of digital signatures, certificates, and cryptographic integrity checks by preventing attackers from generating fraudulent data with the same hash.</li>
        <li>Collision resistance is crucial in maintaining the uniqueness of hashes and protecting against deliberate hash collisions.</li>
    </ul>
<img src="./images/collisionhash.jpg" alt="alternative_text" width="width_value" height="height_value" style="display: block; margin: auto;">
