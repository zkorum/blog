Regarding the privacy vs. security dilemma in the self-sovereign identity space, here are my takeaways from #DICE2023:

JSON-LD BBS+ Verifiable Credentials offer the highest level of privacy among VCs. They support arbitrary zero-knowledge proofs, uncorrelated signatures and identifiers. However, the cryptography they rely on has not yet received official certification, despite its long-standing presence in academia. Additionally, the cryptographic primitives are not supported by existing hardware secure elements.

On the other hand, SD-JWT Verifiable Credentials use well-known and standard cryptography that is supported by secure elements. While they support selective disclosure, they do not support zero-knowledge proofs or uncorrelated signatures/identifiers.

Unlike BBS+ VCs, with SD-JWT Verifiable Credentials, you will need to trust that the Verifier will not collude with the Issuer to gather more information about you based on the cryptographic identifier you reveal. This poses a significant risk, as it could lead to instant traceability of user data in a more powerful way than what is currently possible, while potentially misleading the user with a deceptive perception of privacy through selective disclosure.

Privacy is binary—it is either present or absent. Any compromise means a complete loss of privacy, rather than just a partial weakening.

If data becomes linkable to your real identity in any way, it ultimately relies on trust between parties that can correlate this data. Builders should not rely on this trust alone, as even a trustworthy third-party (a "verifier") can experience data leaks. It is not a matter of if, but when such leaks occur.

Now imagine if this data is tied to a cryptographic identifier that can be correlated with your government ID. It goes beyond random information filled in a web form. It becomes verifiable data, which could lead to a disastrous situation.

That's why at ZKorum , we prioritize privacy and believe in doing what's right, even if it's not easy. If the necessary security primitives are lacking, our approach is to actively work towards implementing them.

What do you think? Protecting privacy or embracing the risk? It's time to reevaluate and prioritize our choices wisely.

#verifiablecredentials #ssi #web3 #cryptography #privacy #cybersecurity
