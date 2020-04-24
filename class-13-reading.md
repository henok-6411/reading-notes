[home page](https://henok-6411.github.io/reading-notes)

# Introduction to JSON Web Tokens (JWT)

 * is an internet standard for creating JSON-based access tokens that assert some number of claims. The tokens are signed either using a private secret or a public/private key. For example, a server could generate a token that has the claim "logged in as admin" and provide that to a client. The client could then use that token to prove that it is logged in as admin. The tokens can be signed by one party's private key (usually the server's) so that party can subsequently verify the token is legitimate. If the other party, by some suitable and trustworthy means, is in possession of the corresponding public key, they too are able to verify the token's legitimacy. 
    JSON WEB TOKEN creates  a secret key, when you resive JWT from a client You can verity by using the secret key of JWT. JWT is simply a string but it has classified by dot in thiree different parts. header ,payload and signatures. 
    
    - example of JWT header payload and signature .
    
    /* 
    var HEADER_HASH = base64(header);
    var PAYLOAD_HASH = base64(payload);
    var SIGNATURE_HASH = base64(signature);
    var JTW = HEADER_HASH + '.' + PAYLOAD_HASH + '.' + SIGNATURE_HASH;
    //JTW ~ xxxx.yyyy.zzzz
    */
    
 * There are many libraries to use JWT in to our application, but we are going to see how to install in Node.js jsonwebtoken package. This package will simplify some work for us , the package will create header part. we don't have to write manually  
    
 
 
 #  fill-in-the-blank 
 
 - JWT stands for JSON______?
 - Ther three parts of JWT are header,______and _____?
 - how do we install the package or module of JWT on node.js _______?
