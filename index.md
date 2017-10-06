This is a list.

    1. Item One
    ```
    new Thing();
    ```

    2. Item Two
    ```
<configuration>
          <property>
              <name>hadoop.tmp.dir</name>
              <value>/var/data/hdfs-tmp</value>
          </property>
          <property>
              <name>fs.s3n.awsAccessKeyId</name>
              <value>S3_KEY_HERE</value>
          </property>
          <property>
              <name>fs.s3n.awsSecretAccessKey</name>
              <value>S3_SECRET_HERE</value>
          </property>
          <property>
              <!-- config valid for clientserver -->
              <name>fs.defaultFS</name>
              <value>file:///opt/iupload/</value>
              <final>true</final>
          </property>
          <property>
              <!-- config valid for clientserver -->
              <name>io.compression.codec.lzo.class</name>
              <value>com.hadoop.compression.lzo.LzoCodec</value>
          </property>
          <property>
              <!-- config valid for clientserver -->
              <name>io.compression.codecs</name>
              <value>
                 org.apache.hadoop.io.compress.DefaultCodec,
                 org.apache.hadoop.io.compress.GzipCodec,
                 org.apache.hadoop.io.compress.BZip2Codec,
                 com.hadoop.compression.lzo.LzoCodec,
                 com.hadoop.compression.lzo.LzopCodec,
                 org.apache.hadoop.io.compress.SnappyCodec,
                 com.hadoop.compression.lzo.LzoCodec,
                 com.hadoop.compression.lzo.LzopCodec
              </value>
          </property>
</configuration>
    ```

    3. Item Three
    ```
    class Foo {}
    ```
