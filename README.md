# nvd-container-gradle
This project builds a Docker image containing [National Vulnerability Database](http://nvd.nist.gov/) in format used by [OWASP Dependency Check](https://github.com/jeremylong/DependencyCheck).
To create the image simply run:
```bash
./gradlew buildImage
```
Implementation notes
---
 * Built using [Gradle](https://gradle.org/) + [gradle-docker-plugin](https://github.com/bmuschko/gradle-docker-plugin)
 * Dataset is stored in [H2](https://www.h2database.com/html/main.html) database
 * [Article describing the implementation](https://github.com/zoomint/nvd-container-image.git)
