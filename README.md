Download .zip file
code for scaling values:
        /* Convert raw data to scaled values */
        myAccelScaled.x = myAccelRaw.x / 8192.0; // 4g scale factor: 8192 LSB/g
        myAccelScaled.y = myAccelRaw.y / 8192.0;
        myAccelScaled.z = myAccelRaw.z / 8192.0;

        myGyroScaled.x = myGyroRaw.x / 65.5;    // 500°/s scale factor: 65.5 LSB/(°/s)
        myGyroScaled.y = myGyroRaw.y / 65.5;
        myGyroScaled.z = myGyroRaw.z / 65.5;
copy inside while if dont use it
