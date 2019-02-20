
# Read Through and Summarization — On Evaluating Adversarial Robustness

**Disclaimer**: this is intended to be a living document, not a traditional one which is written once and never updated.

Check the updates on the Associated GitHub Repo



---

**Original Repo**

[On Evaluating Adversarial Robustness](https://github.com/evaluating-adversarial-robustness/adv-eval-paper?fbclid=IwAR3qX7zu_PCMJ9IGJmcFyypP3JFlW8LVHi-R7xxdBnDUSayoEEQDVlS65aI)



```
Adversarial examples \citep{szegedy2013intriguing,biggio2013evasion},inputs that are specifically designed by an adversary to force a machine learning system to produce erroneous outputs, have seen significant study in recent years.
```

- Objective of the research statement

- Definition of adversarial example (main concept)





```
\subsection{Defense Research Motivation}
``

**Practical**:

- develop defensive strategies (so far attack strategies have progressed more)

- understand worst case: as ML and DL algo become more and more present in business applications, this kind of analysis will probably be more and more required

**Theory**:

- improve understanding of ML and DL algo (long term)

- Adding my 2 cents: possible returns for GANs?





```
\subsection{Threat Models}
```

- Classification and Modeling of Threats (introducing a little bit of standardization)

- This is important to make the research more rigorous (stated more times in the paper)



```
\textbf{Focus on the strongest attacks}
```

This is a methodological point:

- an optimized attack is intended to be a specific starting point for defense related research

- using a suboptimal attack could result in a defense strategy which is suboptimal and easily invalidated by increase the original attack efficiency

- the defense research is intended to completely fix the issue revealed by the original attack (if possible) and fixing the strongest attack possible means fixing on the suboptimal attacks of the same version









