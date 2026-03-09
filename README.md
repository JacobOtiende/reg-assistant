README – Army Regulations Assistant (RAG Chatbot)
BLUF
This tool lets junior leaders and Soldiers ask questions about Army regulations, FMs, and TCs and get clear, BLUF-style answers based on the PDFs loaded into the system.

You use it through a simple chat window in your browser.

What This Tool Is
Purpose: Help leaders understand and apply Army regs in day‑to‑day situations.
What it uses:
PDFs of Army regulations, Field Manuals, and Technical Circulars you provide.
An AI model that:
Finds the most relevant paragraphs.
Writes a clear, BLUF answer.
Who it’s for:
PLs, XOs, PSGs, Squad Leaders, and motivated Soldiers who want fast, reg‑based answers.
How to Use It (Soldier View)
You do not need to know anything about coding to use the tool once it is set up.

Get access

Your unit’s “AI person” / developer will:
Install everything.
Load the regulation PDFs.
Start the app.
They will give you a web link (usually something like http://127.0.0.1:7860 or a unit‑specific address).
Open the chat

Open the link in Chrome/Edge.
You will see a chat box on the screen.
Ask your question

Type your question in plain English, for example:
“What does AR 670‑1 say about beards?”
“What are the counseling requirements for a Soldier consistently late to formation?”
“What are the rules for flagging a Soldier for height/weight failures?”
Press Enter.
Read the answer

The tool will respond with:
BLUF (bottom line up front).
A short, clear explanation.
References to regs or manuals when possible (e.g., “Per AR 670‑1…”).
Follow up

If the answer isn’t exactly what you need, ask:
“Clarify step 3.”
“What reg covers this?”
“Give me an example counseling situation.”
You can keep chatting like you would with a human.
What Questions It’s Good At
Standards & appearance
Hair, beards, grooming (AR 670‑1).
Uniform wear and insignia.
Basic leadership tasks
Counseling situations.
PT failures, height/weight issues.
Writing policy or guidance that aligns with regs.
Administrative processes
Flags, promotions, UCMJ‑related admin basics (within reg context).
“How do I…?” questions
“How do I process X according to reg Y?”
“What are my responsibilities as a squad leader for Z?”
Remember: it can only answer as well as the PDFs you load into it.

What It Cannot Do
It is NOT JAG, SHARP, or Behavioral Health.
For legal, SHARP, suicide, or mental health issues:
Always contact JAG, SHARP, BH, your Chain of Command, or emergency services as appropriate.
It is NOT an official policy source.
It helps you understand and apply regs.
Official policy is still the published regulation/manual.
It does NOT see everything on the internet.
It only knows what’s in:
The reg PDFs loaded into the system.
Its built‑in understanding of general language and Army concepts.
How the Data Works (At a High Level)
All reg PDFs are stored in a local data/ folder.
The system:
Reads those PDFs.
Breaks them into small chunks.
Stores them in a searchable database.
When you ask a question:
It finds the most relevant chunks.
Then the AI writes an answer based on those chunks.
You don’t have to manage any of this as a user; this is for awareness.

Good Habits for Using This Tool
Be specific in your questions:
Good: “For a Soldier on a permanent profile, what does the reg say about PT events?”
Less helpful: “Tell me about PT.”
Ask for the reg:
“Cite the reg and paragraph if possible.”
Verify important decisions:
For anything serious (UCMJ, SHARP, suicide, mental health, EO, etc.), always:
Verify in the actual reg/manual.
Talk to your Chain of Command, JAG, or appropriate staff.
For the Person Setting It Up (Very Short)
If you are the one installing/running this:

Put Army reg PDFs in data/.
Ensure .env has OPENAI_API_KEY.
Install dependencies and run the notebook test.ipynb.
After starting, share the Gradio link with your leaders/Soldiers.
(There can be a separate, more technical README for you if needed.)

Bottom Line
This tool is a reg‑based assistant to help junior leaders and Soldiers get fast, BLUF answers grounded in Army publications, but it does not replace your chain of command, JAG, or official regulations. Use it to get smart quickly, then confirm and execute to standard.