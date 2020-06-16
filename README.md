# notes-careertrack-12.md
### Why you should use bcrypt
<p>The article explained how passwords and usernames are stored. This was very much like what we talked about in class this morning. The author described older ways of passwords(plain test passwords, One way Hash, Salting and random salting) all of which "fall short." BCrypt using a cryptomatic algorithm used as a hash function. BCrypt is extremely resistant to hacks and password cracking/rainbow table(from class).</p>

### Understanding BCrypt
* BCrypt helps to keep human passwords fairly short and memorable due to the advanced hashing function
* crypt was the original and was great except it couldn't keep up with evolving tech power.
* BCrypt protects by slowing down brute force attacks and dictionary attacks. 
* BCrypt requires salt preventing rainbow table attacks.
* BCrypt helps best practices in security with random salting and slowing down passwords against hackers.
 
 ### Where to store JWT
 * In order to prevent cross site scripting and potentially allowing tokens/sensitive data to be seen, you need to safely place the token where it can't be read. 
 * Access tokens can be stored server side or session cookie
 * Some mobile apps store tokens securely with leverage KeyStore/KeyChain for iOS.
 * Tokens can be stored in browser memory...it's believed to be the most secure but it is not persistent.
 * Tokens can be stored in browser local storage which is persistent but less secure and open to attacks. 
