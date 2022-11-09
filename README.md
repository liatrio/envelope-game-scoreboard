# envelope-game-scoreboard

This scoreboard is used to visualize the envelope game score (flow vs. batch) in action.

To use this scoreboard:
1. Clone repo
2. Open the index.html file from finder (mac)
3. Once the game begins, select start
4. Once teams deliver their features in production, select the +1 for the correct group
5. Pause the game at various stages and discuss what's happening 
- 1st Feature in Production - What does this mean?  Value.  Value to Who? 
- How are folks feeling?  Batch / Flow - Stresses?  Relaxed? 
- 6 or 7 Features in PROD - Introduce a Defect - Add a *(Star)
  - Buddies hanging out after work - leaks - there is a mole. 
  - Batch take it back to PO
- Add new Game Changing Feature - Market shift - Create story “A”
- Compare results / output / bonus between PO’s?  Who is doing better batch / flow? 
- Continuous Improvement / Tech Debt Items - Feedback from customer, telemetry, systems - Add a Shape (square, triangle) 
  - Able to adopt an improvement kata 


## Envelope Game: 
Simple demonstration to visualize benefits of continuous flow over traditional large-batch delivery 

Six volunteers are divided into two teams; Flow & Batch.
Roles for each team include: Product Manager, Staff Engineer, & Automation Engineer.

Team Flow Instructions: 
- Product Manager: Responsible for simply writing numbers in sequence on the outside of an envelope and passing the envelope to the next environment. Only one envelope will be worked on at a time.
- Software Engineer: Responsible for receiving envelope from previous environment and writing numbers in sequence on the index card and placing them in the envelope. Then, passing it to the next environment. Only one index card will be worked on at a time.
- Automation Engineer: Responsible for receiving envelope with the index card inside and verifying that the numbers match. If they do, place a sticky note on the index card and place that back into the envelope. 

Team Batch Instructions: 
- Product Manager: Responsible for simply writing numbers in sequence on the outside of an envelope, once you have completed 10, you will send that to the next environment. 
- Software Engineer: Responsible for receiving 10 envelopes from previous environment and writing numbers in sequence on the index card and placing them in the envelope. Then once you have completed 10 you will send that to the next environment.
- Automation Engineer: Responsible for receiving 10 envelopes with the index cards inside and verifying that the numbers match. If they do, place a sticky note on the index card and place that back into the envelope. 
