## python
- .py script --> byte code(mostly hidden) --> PVM(from python.org)

1. Compile to Byte code
    - low level & platform independent
        - byte code runs faster
        - .pyc --> compiled python (frozen binaries)

    - __pycache__
        - source_change & python_version
            - hello.cpython-312.pyc
            - cpython: standard implementation
        - works only for imported files
        - not for top level file
    
2. python virtual machine PVM
    - code loop to iterate byte code
    - run time engine
    - also known as python interpreter

- #### byte code is not machine code
    - python specific interpretation
    - cpython, jython, Iron Python, Stackless, PyPy