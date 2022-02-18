# AlertifyJS WebJar

[AlertifyJS](https://alertifyjs.com/) is a javascript framework for developing browser dialogs and
notifications. This [WebJar](https://webjars.org) includes the corresponding JavaScript and CSS
files. AlertifyJS is licensed under
the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).

WebJars are usually built using a plain Maven POM. This WebJar uses the
[Apache Maven AntRun Plugin](https://maven.apache.org/plugins/maven-antrun-plugin/) to download the
AlertifyJS files from GitHub and puts them into the Java archive.

## Usage

Just include this WebJar into your project. For Maven, you can use the following snippet:

```xml

<dependency>
  <groupId>org.webjars</groupId>
  <artifactId>alertifyjs</artifactId>
  <version>1.13.1</version>
</dependency>
```

And here is a Gradle snippet for you:

```groovy
implementation 'org.webjars:alertifyjs:1.13.1'
```

## Building

Just call

    mvn clean install

and the Jar is built. You can check the output in the target folder. Please make sure that all
required files are included and have proper content.

## Contributing

I highly welcome your updates and improvements. Please open a pull request if you want to contribute
to the AlertifyJS WebJar. Thanks in advance!
