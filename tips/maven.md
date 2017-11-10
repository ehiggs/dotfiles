Building Hadoop:
    time mvn install -Dmaven.javadoc.skip=true -Pdist,native -Djava.awt.headless=true -DskipTests

Building only HDFS:

    time mvn install -Dmaven.javadoc.skip=true -Pdist,native -Djava.awt.headless=true -DskipTests -rf :hadoop-hdfs-project
