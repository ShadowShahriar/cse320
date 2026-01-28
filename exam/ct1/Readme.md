# CT Question (Section 5)

## Scenario 1

A video conferencing application works smoothly at night but suffers noticeable lag during office hours.

1. **Which type of network delay are responsible for this behavior?**

    **Ans.:** In the given scenario, we are told that there is a video conferencing application that works smoothly at night but suffers noticeable lag during the office hours. This noticeable lag occurs due to **network congestion** which increases **queuing delay**.

    However, there are two more delays that might contribute to the lag: **processing** and **transmission delays**.

    **Propagation delay** is not a major factor since it does not change with time of day.

2. **Explain how each delay contributes to the overall E2E delay.**

    **Ans.:** There are three delays that contribute to the noticeable lag in the aforementioned scenario:
    1. Queuing Delay
    2. Processing Delay
    3. Transmission Delay

    Here is how they contribute to the overall E2E delay:

    <ins><strong>Queuing Delay (Primary cause):</strong></ins> During office hours, many users share the network. Routers and switches get congested and the packets wait in _queues_ before being forwarded. This results in significantly longer waiting times. But during night, there are few users sharing the network. So, there are shorter queues and no noticeable performance drop.

    <ins><strong>Processing Delay:</strong></ins> Under heavy traffic, routers process more packets, slightly increasing this delay.

    <ins><strong>Transmission Delay:</strong></ins> During congestion, effective available bandwidth per user drops, increasing transmission time. This can worsen real-time video performance during peak hours.
