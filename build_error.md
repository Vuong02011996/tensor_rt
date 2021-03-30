## Open cv
1.  OpenCV(4.2.0) ../modules/core/src/matrix.cpp:235: error: (-215:Assertion failed) s >= 0 in function 'setSize'
    
    ```img is None, error directory```

2. OSError: libcublas.so.10: cannot open shared object file: No such file or directory
   
    ```
    conda install -c anaconda cudatoolkit=10.1
    sudo cp -r libcublas.so.10 /usr/local/cuda/lib64
   ```
2.  ERROR: coreReadArchive.cpp (41) - Serialization Error in verifyHeader: 0 (Version tag does not match. Note: Current Version: 96, Serialized Engine Version: 87)