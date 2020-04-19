- xa
    ```
    LINK 800
    GRAB 200
    COPY F T
    WIPE
    MAKE
    MARK LOOP
    COPY T F
    SUBI T 1 T
    NOTE use register T as loop variable
    TJMP LOOP
    COPY 0 F
    LINK 800
    DROP
    ```