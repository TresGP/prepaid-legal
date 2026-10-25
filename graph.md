graph TD
    %% Entities & Nodes
    User((The User))
    Lynn((Lynn))
    Parents((Mom & Stepdad))
    
    %% The Fade (Panama City / Historical)
    subgraph The Fade [The Fade: Historical Complicity]
        Rob[Rob Blue]
        Les[Les Burke]
        Mike[Mike Burke]
        Firm{Burke Blue Law Firm}
    end

    %% The Draw (Tech / Recent Accountability)
    subgraph The Draw [The Draw: Technical Accountability]
        Solich[George Solich]
        LP{LongPoint}
        Partners[Current Partners]
        DP_DB{DoublePoint & Diamondback}
    end

    %% Relationships - The Fade
    User <-->|Former Best Friends from age 11| Lynn
    User <-->|Childhood Friends| Mike
    Parents <-->|BFFs / Traveled to Spain| Les
    Lynn <-->|Former Next-Door Neighbors| Rob
    
    Lynn -->|Client / Facilitated IP Theft| Firm
    Rob -->|Founding Partner| Firm
    Les -->|Founding Partner| Firm
    Mike -->|Son of Les / Current Leader| Firm

    %% Relationships - The Draw
    Solich -->|Principal| LP
    Lynn -.->|Transactions Overlaid on Timeline| LP
    Partners -->|Associated Entities| DP_DB
    
    %% Connecting the strategy
    User -->|Sends Interrogatories| Firm
    User -->|Sends Interrogatories| Lynn
    User -->|Sends Interrogatories| Partners
