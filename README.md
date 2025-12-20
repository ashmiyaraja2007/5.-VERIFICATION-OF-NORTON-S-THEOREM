# 5.VERIFICATION-OF-NORTON-S-THEOREM
**NAME : ASHMIYA.R**
**REFRENCE NUMBER :25001337**
**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/432f8370-249f-40d0-b96e-186091e001d3" />


**To measure IL**
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/c2cd9ec2-77d0-460e-bd29-38a15bd08128" />



**To measure RTh or RN**
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/f39eeab0-df6d-4450-ba00-81b1490722f5" />



**To measure IN or Isc**
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/66007eca-ccc7-44d1-a53a-f9a9fd7331ee" />


 
**Thevenin’s equivalent circuit**
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/01ee56c3-d21b-456b-90b9-2a0db9f1bf64" />


**Norton’s equivalent circuit**
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/d27c6da6-bd0f-473e-9164-e9fa606bd2c7" />


**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 1**
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/283248c4-fb0a-415d-8475-1da07cd1b2d9" />

To measure I L

Vi (volts)	IL (amps)

**TABULAR COLUMN:2**
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/26193a5f-b60c-4765-954c-c7cc19c7a7f9" />


To measure RTh or RN

Vi (volts)	RTh (Ω)


**TABULAR COLUMN:3**
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/9f5de35b-b50f-4a47-bb6b-0042f3db4076" />


To measure IN or Isc

Vi (volts)	IN (amps)
	
**MODEL CALCULATION:**
<img width="937" height="1431" alt="image" src="https://github.com/user-attachments/assets/4ac5d88c-9530-440c-81cd-3d27dfadca43" />
<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/70c47aee-6a06-4a1d-ab13-3bf9034fa9be" />



Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
 ** MARKS SPLIT UP:**
 <img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/7d0d9bbf-a230-4678-bedc-bed12204f328" />



**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
