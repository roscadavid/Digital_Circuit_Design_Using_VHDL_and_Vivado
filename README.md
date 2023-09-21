# Digital Circuit Design Using VHDL and Vivado Program

I implemented a JK flip-flop using a 4:1 multiplexer and logic gates in VHDL code. I received a state transition diagram for the automaton, as well as a table showing how the flip-flop operates on a falling clock edge. I will present each step I followed in completing the project:

Step 1: I worked out the state transition diagram on paper (in PDF format) and used the JK flip-flop truth tables.

Step 2: Using the truth table (from step 1), I implemented an automaton composed of three JK flip-flops and three 4:1 multiplexers. Since the flip-flop is relatively simple, I obtained only one logic gate, which is an inverter.

Step 3: After solving the project requirement on paper, I proceeded to implement the JK flip-flop in Vivado. Here, I used the provided table, noticing that the flip-flop operates on a falling clock edge, and the reset is active low according to the table.

Step 4: After implementing the VHDL code for the falling-edge triggered JK flip-flop, I implemented the VHDL code for the 4:1 multiplexer (the code can be found in the PDF).

Step 5: I built the sequential automaton as calculated on paper but translated it into VHDL code. Here, I needed all the components from the JK flip-flop, the 4:1 multiplexer. I created five signals: "net" as a vector of logic type, "Qin" as a vector of logic type, "Q0_neg," "Q1_neg," "Q2_neg." Afterward, I connected each of them within the automaton.

Step 6: I simulated the 4:1 multiplexer to check if it functions correctly.

Step 7: I performed a simulation in Vivado for the JK flip-flop to ensure it operates correctly.

Step 8: Finally, I implemented the VHDL code for the sequential automaton and simulated it. During simulation, we obtain a state transition diagram, indicating that the digital circuit is functioning correctly.
