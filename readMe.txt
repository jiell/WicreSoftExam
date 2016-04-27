将本地jar包放到本地maven仓库
mvn install:install-file -Dfile="D:/xxx/common.jar" -DgroupId=com.examstack -DartifactId=common -Dversion=2.0.0 -Dpackaging=jar 