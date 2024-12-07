This repository contains a simple COBOL program demonstrating a potential bug related to the MOVE statement. The bug arises because the compiler's handling of the MOVE statement might vary. In some environments, if the receiving field is larger than the sending field, padding might occur, and if the receiving field is shorter than the sending field, truncation might occur.  This simple example highlights the importance of careful data handling in COBOL and the need to verify that the size and type of data being moved are consistent.