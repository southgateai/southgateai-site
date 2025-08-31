---
title: 'Industry'
date: 2024-01-01
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: markdown
    content:
      title: 'The State of Industry'
      subtitle: 'AI creators, Cybersecurity firms and their corporate customers'
      text: |-
        To sum up, **there is not much focus on defensive techniques**.
        
         - Those in the AI sector focus on getting their stuff to work.  [AI alignment](https://en.wikipedia.org/wiki/AI_alignment) is their principal approach to preventing problems.
         - The Cybersecurity industry knows about the industry's potential to control powerful AI but rarely pursues or talks about it.
         - Or when they do, it's marketing-led.  There are plenty of examples if you search for [AI-powered malware](https://www.google.com/search?q=AI-powered+malware).
        > {{< figure src="darktrace-ai-powered-malware.png" id="darktrace-ai-powered-malware" >}}
        
        They don't talk about threats that might be one or more years in the future, as it's not good marketing and might harm their credibility for no or little gain.
         - Corporate customers generally aren't aware of or are suspicious of the marketing.
  - block: markdown
    content:
      title: 'It''s not all bad'
      subtitle: 'This group knows things...'
      text: |-
        On the plus side, industry **knows things that other groups might not**.
        
         - AI alignment[[@wiki]](https://en.wikipedia.org/wiki/AI_alignment) - controlling AI by giving it a benevolent set of goals - is neither easy nor great at its job.
           - Not least because once powerful AI technology exists it can just be repurposed with a more dangerous set of goals.
         - The idea of 'sensor' software on countless millions of computers, sending a second-by-second account of what that computer is doing, for complex problem-spotting analysis and response in the cloud.  It might sound far-fetched and unachievable, but it already happens every day.
  - block: markdown
    content:
      title: 'Defense as an antidote to regulation'
      subtitle: ''
      text: |-
        The mood music suggests regulation is on the way, and that regulation is likely to arrive long before the AI capability it's intended to regulate.  So several things might happen:
        
         - Corporations with a vested interest in minimizing regulation might propose defensive measures as an alternative.  These would likely be provided, at least in part, by one or more external agents, which themselves are regulated.
         - Governments might make defensive measures mandatory for high-capability AI projects.
         - Telemetry will likely be bundled with defenses to ensure compliance and give advance warning of risk.
        
        None of these are bad outcomes compared to uncontrolled AI development, or regulation that slows AI progress in some jurisdictions, only to allow less cautious operators to get ahead.
        
        This might, and probably should, prove to be such an advantage for the major players in AI that it leads them to fund or create defensive projects themselves.
  - block: markdown
    content:
      title: 'The barrier to entry is not that high'
      subtitle: '...because of App Stores'
      text: |-
        Fortunately, you don't need to build large-scale cloud infrastructure and manage millions of installed sensors yourself, because the people that do have App Stores.  [Here's one](https://www.sentinelone.com/partners/singularity-marketplace/), [and another](https://store.crowdstrike.com/).  Put simply, you can build your own app to consume the event streams from these platforms and make its own judgments about whether the activity is good or bad.  Now, this would be a mere shadow of the system you'd need to manage superintelligent AI, but current AI is also a mere shadow of superintelligent AI.  All an app has to do is prove viability and provide some value to gain a foothold.  Its capability can then be extended as required.
  - block: markdown
    content:
      title: 'Cybersecurity firms'
      subtitle: 'The firms to focus on'
      text: |-
        The focus is on companies with sensor-based technology that feeds data into a larger Cloud ecosystem.
        
         - [Microsoft](https://www.microsoft.com/), with a larger interest in Cybersecurity [than you might think](https://www.microsoft.com/en-us/cybersecurity).
         - [CrowdStrike](https://www.crowdstrike.com/).  For full disclosure - the author's employer.  I don't speak for them, but I do get the insider's viewpoint.
         - [Trend Micro](https://www.trendmicro.com), with reference to their [endpoint sensor](https://www.trendmicro.com/en_hk/business/products/user-protection/sps/endpoint/endpoint-sensor.html).
         - [SentinelOne](https://www.sentinelone.com/).
         
        These are the companies carrying the fight right now.
        
        {{< spoiler text="Click to view the Sector Leaders" >}}
        {{< figure src="gartner-leaders-2021-05.png" id="gartner-leaders-2021-05" >}}
        {{< /spoiler >}}
  - block: markdown
    content:
      title: 'GDR - General Detection and Response'
      subtitle: ''
      text: |-
        Will we see another era of cybersecurity?
        
         - **EDR[[@wiki]](https://en.wikipedia.org/wiki/Endpoint_detection_and_response) - Endpoint Detection and Response** (2013).  Technology that continually monitors an "endpoint" (for example a laptop, mobile phone, IoT device) to mitigate threats.
         - **XDR[[@wiki]](https://en.wikipedia.org/wiki/Extended_detection_and_response) - Extended Detection and Response** (2018). Technology that continually collects and correlates data across various network points such as servers, email, cloud workloads, and endpoints to mitigate threats.
         - **GDR - General Detection and Response.**  Technology that continually collects and correlates data from all relevant sources to mitigate threats from Artificial General Intelligence.
        
        If so, the field is wide open.
        
        To see *why* GDR might become the Next Big Thing, head on over to the [Defensive Argument](/defensive) page.
---
