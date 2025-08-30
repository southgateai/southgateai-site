---
title: 'The Defensive Argument'
date: 2024-01-01
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: markdown
    content:
      title: '<i>''History is merely a list of surprises,'' I said. ''It can only prepare us to be surprised yet again.''</i>'
      subtitle: '<div style="font-size&#58; 12pt; text-align&#58; right;">Kurt Vonnegut</div>'
      text: |-
        In the future, there will be powerful AI, and there will be defenses trying to ensure that good things happen and bad things do not.  Those defenses might simply be a human within reach of an off switch, or they might be the most comprehensive and effective defense system that it's possible to create.
        
        As you turn the dial as to how powerful the defenses are, at some point, the defenders win.  In predicting the future we need to decide how far it's possible to turn that dial, and whether anything prevents us from turning it far enough.
        
        **Can defensive measures be good enough?**
  - block: markdown
    content:
      title: '<i>Rules doesn''t really mean just rules</i>'
      subtitle: '...at least in the text below'
      text: |-
        <div class="fa-3x"><i class="fa-solid fa-ruler fa-beat" style="--fa-beat-scale: 1.35;"></i></div>When talking about <strong>rules</strong>, what I mean is a complex, distributed, live-updating system of static, behavioural and historical analysis with many, many components using many techniques, using the same level of technology as the AI it's analysing.  AI introspection, monitoring input and output, and looking for bad patterns of behaviour are only parts of that system.  This is just a continuation of the story we're already seeing in current cloud-based cybersecurity.
  - block: markdown
    content:
      title: 'The list of things that won''t work or that we can''t do'
      subtitle: ''
      text: |-
        A brief and incomplete list of ways to fail, just so we know we're on the same page.
        
         - **Create a good superintelligent AI.**  Due to the Alignment Problem[\[@wiki\]](https://en.wikipedia.org/wiki/AI_alignment) this ends badly.
         - **Create a good superintelligent AI to combat any bad superintelligent AI.**  At the risk of saying "See above", for various reasons, mostly the Alignment Problem again, this doesn't work.  The one caveat is that maybe this is an easier alignment problem to solve, but let's not count on it.
         - **Try to not create powerful AI at all.**  We show no signs of resisting that temptation, nor any clear way to do so.
         - **Allow the superintelligent AI to get full knowledge of the defenses it's facing, and the knowledge that it has full knowledge.**  Once it knows it has all the information it can formulate a plan to escape.
         - **Use a static, unchanging set of rules in your defenses to determine whether the AI should be allowed to continue**.  If you do this, the AI will eventually get knowledge of full knowledge as above.
         - **Use rules running exclusively on the same hardware as the AI.**  Again the AI can gain full knowledge.
         - **Allow the AI multiple attempts to probe the rules of the defense.**  This allows the AI to discover the rules by trial and error.  This includes allowing the AI to replicate in a regime where the defensive measures *don't* stop *all* of the replicas when one breaks the rules.
         - **Allow the AI to learn from other AIs (that don't care about being stopped) breaking the rules until eventually, one finds a way to escape without being stopped, and the original AI knows it faces the same rules.**  Either rapid rule updates or different sets of rules can help here.
         - **Allow anything, including the AI, to compromise the rule-enforcing system.**  A successful attempt to disable the rule system leads to trouble, although obviously, any attempt to do that against the rules too.
         - **Use just a single method or a handful of methods to detect bad behaviour**.  This runs the risk of the AI predicting what you've done.
  - block: markdown
    content:
      title: 'It''s not all bad, some things favour the defender'
      subtitle: ''
      text: |-
        - **For the AI, it's not sufficient to discover all of the rules the defenders are using to detect badness.**  It also needs to be sure that it knows all of the rules.  It needs knowledge that it has complete knowledge, which is difficult, especially if the rules can change.
         - **Each AI need only be given one chance.**  If it breaks the rules we can stop it and never allow it to run again.
         - **Generally, we get to design the hardware the AI runs on.**  So we can build in whatever safeguards we want, and force the AI to fabricate its own silicon (or equivalent) to fully escape them.
         - **Physical weapons are still a thing.**  Any agency or nation-state trying to build AI systems without these safeguards is potentially subject to attack.  Deliberately trying to build a Doomsday AI, or even acquire the unfettered capability to do that, is likely to get you nuked, and you need to be very sure you can do it in secret before you try.
         - **All computer systems will need this type of protection anyway.**  Malware and malicious attack techniques, including those boosted by weak-ish AI, are likely to become so advanced that unprotected hardware connected to the network is rapidly compromised.
         - **The AI has to get information from somewhere, and we can monitor what it's looking at.**  It won't be as easy as seeing it search for "How to destroy humanity and get away with it"[\[@google\]](https://www.google.com/search?q=How+to+destroy+humanity+and+get+away+with+it) but its patterns of interaction with the outside world can give away something.
         - **The AI can't just sit there silently plotting, then suddenly launch a devastating attack.**  It needs to stay current with what's happening in the world to be sure of a successful attack, although it *can* be deceptive about how it does that.
         - **The AI can try to deceive us but we can also try to deceive it.**  We can potentially trick it into revealing what it's going to do.
         - **AI introspection - seeing how the AI is making decisions - might help to some extent.**  It's difficult to forecast how well this might work, but you could monitor the internals of an AI as you, say, ask it a set of 10,000 questions.
        
        Saving the biggest until last:
        {{% callout note %}}
        There is a **lot** of money in cybersecurity.  Billions of dollars are spent annually, much of it finding its way into R&D.  For cybersecurity firms, the incentives are the right way around.  Ensuring AI safety isn't a costly distraction from AI development, it's a core revenue-generating business, which makes it easier to get resources and engineering time applied to it.
        {{% /callout %}}
  - block: markdown
    content:
      title: '<i>It is not clear which side wins</i>'
      subtitle: 'Whether we reach Nirvana, Doom, or meander somewhere in between'
      text: |-
        <div class="fa-3x"><i class="fa-solid fa-balance-scale fa-beat" style="--fa-beat-scale: 1.35;"></i></div>It is not a clear win for either side, which is OK, because that means it's not definitely Doom.  It <i>feels</i> like, the more effort we put into defenses, and the earlier we start, or the better we time things, the better chance of a good outcome.
  - block: markdown
    content:
      title: 'Is there a viable steady state we can get to?'
      subtitle: 'Is there any stable end state at all that we can claim to be a good outcome?'
      text: |-
        If we conclude that there is no stable end state that includes powerful AI, the universe inevitably moves towards a state where singularly focused AIs merely battle it out for resources with no higher purpose, then we're in a quandary.  Fortunately, some of our [natures of reality](/reality) largely forbid that, so it's not time to give up, at least until we know what reality we're in.  But is there such a stable state, even in tricky natures of reality and if so, how do we get to it?
        
        The worlds of Physicalism seem the most difficult.  Does a large number of AIs that all police each other represent a stable state?  Or do the most single-minded resource gatherers gradually win out, doing everything they can to enhance their own computational power in an attempt to attain supremacy?
        
        Many of these long-term doom scenarios are fragile and vulnerable to new discoveries in physics that might happen along the way.  For me, it's not possible to predict the future to a degree where we can say that there is no viable steady state.  It is simply up to our future selves to plot a way toward it as the way becomes clear.
        
        Whether this steady state of Nirvana exists or not, it's still possible to **miss it entirely and end up with very bad things**.  So **that** is what we're trying to avoid.
  - block: markdown
    content:
      title: 'What about deliberately weaponized AI?'
      subtitle: 'AI purposefully running on platforms without any of these protections'
      text: |-
        One case where defenses don't work is if they're deliberately not present, or even if there are anti-defenses to make an AI catastrophe *more* likely.  One scenario might be hostilities between nations, where one side wants a Doomsday Device it can use to threaten annihilation.  An AI given goals very hostile to the other side and actively aided in its attempt to achieve world domination.
        
        For once, the prospective impossibility of AI Alignment actually helps, albeit we find ourselves relying on Mutually Assured Destruction, again.  Such a weaponized AI couldn't be reliably targeted only at the other side and would stand a strong chance of also destroying its creator.
---
