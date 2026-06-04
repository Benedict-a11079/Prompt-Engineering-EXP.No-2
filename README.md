EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:
Text summarization 
Technique 1 — Zero-shot 
Prompt: 
Summarize the following article on blockchain technology 
in 100 words or fewer, suitable for an undergraduate 
student with no prior technical knowledge. 
ChatGPT output: 
Blockchain is a digital record-keeping system that stores data across 
thousands of computers simultaneously, making it nearly impossible to 
alter or hack. Originally created for Bitcoin in 2008, each "block" of data is 
linked to the one before it using a unique code, forming a secure chain. No 
single person or organisation controls it — instead, a network of computers 
verifies every transaction. Beyond cryptocurrency, blockchain is being used 
in healthcare, supply chains, and even voting systems. Its key strengths are 
transparency, security, and the removal of the need for a central authority 
like a bank. 
Gemini output: 
Think of blockchain as a shared Google Doc that thousands of people have 
a copy of — but nobody can erase what's already written. It records 
transactions in "blocks" linked together in a chain. Invented in 2008 for 
Bitcoin, it now powers smart contracts and supply chains. Because every 
computer in the network holds a copy, there is no central point to hack. 
Changes require agreement from the majority of the network, making it very 
secure and trustworthy without needing a bank or government in the 
middle. 
Claude output: 
Blockchain is a decentralised digital ledger — essentially a record book 
stored simultaneously across thousands of computers rather than on one 
central server. Created in 2008 as the foundation for Bitcoin, it records 
transactions in "blocks" that are cryptographically linked in sequence. 
Altering a past block would break the chain, making tampering evident. No 
single authority controls it; instead, the network reaches agreement 
through consensus rules. Smart contracts — self-executing code stored on 
the blockchain — extend its use to healthcare, supply chains, and 
governance, wherever secure, transparent records are needed. 
Copilot output 
Blockchain is a type of database that stores information in linked "blocks" 
across a network of computers rather than in one central location. First 
developed for Bitcoin in 2008, it is now used in many industries. Its main 
features are: it is decentralised (no single owner), immutable (past records 
cannot be changed), and transparent (everyone on the network can verify 
transactions). Smart contracts automatically execute agreements without 
middlemen. Blockchain's potential reaches into supply chains, healthcare, 
and electronic voting, though challenges like energy use and scalability 
remain. 
Technique 2 — Few-shot 
Prompt: 
Here are two examples of good student-friendly 
summaries: 
Example 1 — DNA replication: "DNA replication is how 
cells copy their genetic code before dividing. An enzyme 
called DNA polymerase unzips the double helix and builds 
two identical strands — so each new cell gets the full 
instruction set." 
Example 2 — Machine learning: "Machine learning 
teaches computers to improve from experience instead of 
being explicitly programmed. By feeding algorithms large 
datasets, the model learns patterns and can then make 
predictions on new data." 
Now summarize this article in the same style — 2 to 3 
sentences, plain language, no jargon: 
ChatGPT output: 
Blockchain is a digital ledger shared across thousands of computers, 
where every transaction is recorded in a "block" that links to the previous 
one — making it practically impossible to alter past records. Originally built 
for Bitcoin, it removes the need for central authorities like banks by letting a 
network of computers collectively verify and approve transactions. Today it 
powers everything from smart contracts to supply chain tracking, oAering a 
new way to store and share information that is secure by design. 
Gemini output: 
Blockchain is a shared digital record book that is copied across thousands 
of computers at once, so no single person or organisation controls it and no 
past entry can be quietly changed. Each new piece of data is bundled into a 
"block" and chained to the one before it using a unique code, meaning the 
history is locked in. Beyond Bitcoin, it now automates agreements via 
smart contracts and makes processes like tracking parcels or medical 
records more trustworthy and transparent. 
Claude output: 
Blockchain is a way of storing records not in one place but spread across a 
network of computers, where every entry is linked to the last so that 
nothing can be changed without everyone noticing. It was first built for 
Bitcoin in 2008 and works without banks or governments — the network 
itself agrees on what is true through shared rules. Its applications now 
stretch from automatically enforcing contracts to securely tracking medical 
records and goods through supply chains. 
Copilot output: 
Blockchain is a decentralised digital ledger that records transactions 
across a network of computers, where each block is linked to the previous 
one using cryptographic hashes, making it resistant to tampering. It was 
originally designed for Bitcoin but has since expanded to applications in 
smart contracts, healthcare, and supply chains. Its transparency and 
immutability make it a powerful tool for creating trust without the need for a 
central authority. 
Technique 3 — Chain-of-thought: 
Prompt: 
Read the article carefully. Before writing the summary: 
Step 1 — Identify the 3 most important concepts the 
student must understand. 
Step 2 — List any jargon that needs simplifying and write a 
plain-language replacement. 
Step 3 — Write a final 80–100 word summary using only 
plain language. 
Show your reasoning for steps 1 and 2, then present the 
final summary clearly labelled "Final summary:". 
ChatGPT — reasoning + output: 
Step 1 — Key concepts: (1) Decentralisation — no central authority; (2) 
Immutability — data cannot be changed once recorded; (3) Consensus 
mechanisms — how the network agrees on what is true. 
Step 2 — Jargon simplifications: "Cryptographic hash" → "unique fingerprint 
code"; "Consensus mechanism" → "network voting system"; "Smart 
contract" → "automatic agreement program"; "Immutability" → "permanent, 
tamper-proof record". 
Final summary: 
Blockchain is a digital record book copied across thousands of computers 
rather than stored in one place. Every entry is sealed with a unique 
fingerprint code that links it to the previous one — so altering any record 
would break the chain and alert the whole network. No bank or government 
runs it; instead, the computers vote together to approve each new entry. 
Programs called smart contracts can automatically carry out agreements 
when conditions are met. Beyond Bitcoin, blockchain is now used to track 
medicines, goods, and even votes securely. 
Gemini — reasoning + output: 
Step 1 — Key concepts: (1) A distributed ledger that no one owns; (2) 
Blocks chained by a code that makes past data permanent; (3) Smart 
contracts that self-execute without middlemen. 
Step 2 — Jargon simplifications: "Decentralised" → "owned and run by 
everyone equally"; "Cryptographic hash" → "a tamper-revealing seal"; 
"Proof of Work/Proof of Stake" → "the rules the network uses to decide who 
adds the next block"; "Immutability" → "once written, it stays written". 
Final summary: 
Imagine a public notebook that thousands of people hold a copy of — and 
every time someone adds a page, everyone's copy updates instantly. That's 
blockchain. Each page (block) carries a tamper-revealing seal from the 
previous one, so quietly changing old entries is impossible. No single bank 
or company controls it; the whole network votes on what gets added. 
Special programs called smart contracts can automatically trigger actions 
— like releasing a payment — when agreed conditions are met. This 
technology already powers Bitcoin, healthcare records, and tamper-proof 
supply chains. 
Claude — reasoning + output: 
Step 1 — Key concepts: (1) The chain structure — how blocks link and why 
that makes tampering visible; (2) Decentralisation — why no single entity 
controls the ledger; (3) Smart contracts — self-executing programs that 
remove intermediaries. 
Step 2 — Jargon simplifications: "Cryptographic hash" → "a unique identity 
code that changes if the data changes"; "Consensus mechanism 
(PoW/PoS)" → "a network-wide agreement process for approving new 
entries"; "Decentralised" → "spread across many computers with no single 
owner"; "Immutable" → "permanently locked; cannot be quietly edited". 
Final summary: 
Blockchain is a record-keeping system spread across thousands of 
computers so no single person or company controls it. Every new entry — 
called a block — gets a unique identity code based on the entry before it. 
Change any old block and its code breaks, alerting the entire network. This 
makes the record permanent and tamper-proof. Computers on the network 
vote together to approve every new addition. Blockchain also runs smart 
contracts: automatic programs that carry out agreements the moment set 
conditions are met. Uses include Bitcoin, tracking medicines, securing 
votes, and managing supply chains. 
Copilot — reasoning + output 
Step 1 — Key concepts: (1) Distributed ledger technology — no central 
database; (2) Immutability via cryptographic linking; (3) Smart contracts 
and real-world applications. 
Step 2 — Jargon simplifications: "Cryptographic hash" → "a digital 
fingerprint"; "Decentralised" → "stored on many computers, not one"; 
"Consensus mechanism" → "network agreement process"; "Immutable" → 
"cannot be changed once recorded". 
Final summary: Blockchain is a digital record system stored on thousands 
of computers at once rather than one central database, so no single person 
or company controls it. Every set of transactions is packaged into a block, 
stamped with a digital fingerprint of the block before it, and locked 
permanently — meaning any attempt to change old records is immediately 
detectable. The network agrees collectively on what gets added. Smart 
contracts — automatic programs on the blockchain — carry out 
agreements without middlemen. This technology underpins Bitcoin and is 
being applied in healthcare, logistics, and secure voting. 
 
 
 
Prompt 
technique Platform Accuracy Coherence Simplicity Speed UX Total 
/25 
Zero-shot 
ChatGPT 5 4 3 5 4 21 
Gemini 5 5 4 5 5 24 
Claude 5 4 3 4 3 19 
Copilot 5 3 3 4 3 18 
Few-shot 
ChatGPT 5 5 4 4 4 22 
Gemini 5 5 5 4 5 24 
Claude 5 5 5 4 4 23 
Copilot 5 3 3 4 3 18 
Chain-of
thought 
ChatGPT 5 5 5 3 5 23 
Gemini 5 5 5 3 5 23 
Claude 5 5 5 3 5 25 
Copilot 5 5 4 3 4 21 
pdf link:[Uploading Ex2.text.summarization.across.different.platforms.pdf…]()

RESULT:
The experiment completed and output is verified
