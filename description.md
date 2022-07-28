# Information on the talk
The talk was handed in with the following title and description.

## The title
IRMA's Idemix core: Understanding the crypto behind selective, unlinkable attribute disclosure

## Short description
IRMA is a system in which you are in control of sharing specific personal properties (aka attributes) such as your age, address and gender which are stored in the IRMA app on your phone. Technically, IRMA is a set of free and open source software projects implementing the Idemix attribute-based credential scheme. Although the Idemix credential system has been around for a while it is still relevant today. In this talk, we walk you through the crypto behind Idemix, explain how it works, why it is safe and give you the means to understand Gabi, the Go implementation of Idemix that is used in IRMA.

## Detailed description
Presentations on privacy products often focus on the principles of why we should want to protect our privacy and how the product does this from a birds-eye or user perspective. In case of IRMA, this focus would be on storing your attributes on your local device and on the information flow when the IRMA app is used.

However, in this talk we want to dig deeper, demonstrate the crypto behind the curtains and give you the means to reason why IRMA is a neat solution.

Note that the talk is very technical. We will cover the theory of the zero-knowledge proofs, the Camenisch-Lysyankaya signature and the Idemix credential verification, all so you can understand the Go implementation of the Gabi library. If time allows, we'll also cover IRMA-specific solutions such as the keyshare protocol and revocation.

We will cover a lot of ground very quickly but after this talk you will have an excellent starting point for truely understanding this anonymous credential system. Of course we'll provide you with follow-up material and are happy to chat some more after the talk with a beer or two.

Background knowledge that will help in understanding this talk:
- General understanding of public key cryptography, especially RSA (https://www.youtube.com/watch?v=MsqqpO9R5Hc, https://www.youtube.com/watch?v=SL7J8hPKEWY)
- Basic algebra, namely laws of exponentiation
- Some context on IRMA (https://irma.app/docs/overview/)

