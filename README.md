# hunafuserver

Add the following line (with your custom "docBase") to your tomcat server.xml

      <Host name="localhost"  appBase="webapps"
            unpackWARs="true" autoDeploy="true">

        <Context path="/hunafuserver" docBase="/Users/nihits/UnityProjects/HuNaFu/HunafuServer/" reloadable="true" allowLinking="true" />
        
        ....
        
      </Host>
