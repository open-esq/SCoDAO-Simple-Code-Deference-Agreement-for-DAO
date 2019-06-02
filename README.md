# SCoDAO – Simple Code Deference Agreement for DAOs

This is a work-in-progress alpha version of a SCoDAO, or Simple Code Deference Agreement for DAOs based on [Gabriel Shapiro's SCoDA](https://github.com/lex-node/SCoDA-Simple-Code-Deference-Agreement-). It is designed to provide a model for the type of legal or ‘wet’ contract that may be entered into by [digital organization](https://aragon.org) (or "DAO") participants (the "parties") who wish to otherwise agree that ‘code is law’ with respect to this governance protocol among them. In this case, the ‘code’ is a set of persistent programs (or "smart contracts") deployed to the Ethereum blockchain network ("Ethereum") that might retain or transfer pooled assets and/or organization permission(s) according to the parties' executed (or "signed") digital transactions. 

The SCoDAO provides that, after the parties sign the SCoDAO, the results of operations of their DAO smart contracts will be binding upon, and thus non-appealable by, the parties with respect to their DAO assets and transactions (as well as any proceeds thereof), subject to certain (narrow) exceptions. 

The SCoDAO therefore embodies a “qualified code deference” (QDC) approach to smart contracting as eloborated by [Gabriel Shapiro] (https://github.com/lex-node/). As compared to competing approaches to smart contracting (such as the ‘Ricardian’ approach or the unqualified ‘code is law’ approach): 

* QDC does not try to describe or summarize a contractual arrangement the code is supposed to perform;

* QDC does not try to make the code itself a written text intended to express a legal agreement; 

* QDC does not try to make a ‘machine-readable’ version of a natural language contract; and 

* QDC does not provide that the results of operating code are binding in absolutely all cases.

Rather, QDC contemplates that SCoDAO is designed to be a legally binding contract whereby the parties agree that, EXCEPT in certain narrow circumstances, they will DEFER to (i.e., refrain from disputing in a legal proceeding) the results of operation of a smart contract. While a detailed explanation of the motivations for, and pros and cons of, the QDC approach is pending, a cursory explanation of the approach can be found here: 
https://twitter.com/lex_node/status/1028727470210437120 
and here: https://twitter.com/lex_node/status/1019819161298456577

The exceptional circumstances under which the parties are not required to defer to the smart contract are captured under the concept of a “Material Adverse Exception Event.” These circumstances are basically the blockchain equivalent of ‘force majeure’ events—e.g., a 51% attack that causes a double-spend somehow affecting the smart contract. Although, under such a narrow definition, Material Adverse Exception Events should be incredibly rare, the SCoDAO provides a standstill provision and a set of negotiation and arbitration procedures designed to drive the parties toward a resolution of how to handle one if it occurs. Of course, parties in the wild may opt for an even narrower version, or a broader version, of “Material Adverse Exception Event,” depending on their particular preferences.

Additionally, like any contract, the SCoDAO contains fundamental representations and warranties from the parties to the effect that they have the capacity and authority to enter into the Agreement, as well as slightly more specialized representations whereby each party represents that it is sophisticated or has been advised by someone sophisticated in reviewing code and thus has thoroughly evaluated the code of the smart contract. 

The SCoDAO also binds the parties to narrow contractual covenants intended to bolster the intended code deference, such as that the parties shall not bring legal proceedings to contest the results of the smart contract (unless there is a Material Adverse Exception Event) and shall not grant any liens on or purport to sell or transfer any of the tokens held in the smart contract. 

If any of the representations and warranties or covenants of a party is breached, the non-breaching party would have the right to bring an indemnification claim against the breaching party for any damages of the non-breaching party arising from such breach. In the current version of the SCoDAO, this would mean initiating a meatspace claims process culminating in an arbitration. 

It must be emphasized that this is an ALPHA release of a MODEL form. Thus: 

* it is very much a work in progress

* it likely has various glitches, bugs and imperfections; and 

* even in its final version, it will not be intended to be a contract that actually can be signed-- ‘off-the-shelf,’ as it were-- by parties who wish to do a deal. 

Among other lacunae in the contract, there is no ‘Exhibit A’ setting forth the arbitration procedures, since presumably these will vary quite a bit depending on the parties’ preferences. 

## License

This project is licensed under the Creative Commons Attribution-ShareAlike 4.0 International Public License - see the [LICENSE.md](LICENSE.md) file for details
