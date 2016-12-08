To reproduce bug, run

   sbt-tg test

   [info] Resolved coursier-spaces dependencies
   [trace] Stack trace suppressed: run last *:coursierResolution for the full output.
   [error] (*:coursierResolution) coursier.ResolutionException: Encountered 1 error(s) in dependency resolution:
   [error]   org.jboss.spec.javax.ws.rs:jboss-jaxrs-api_2.0_spec:1.0.0.Final
   [error]         :
   [error]     download error:
   [error]       Caught java.net.MalformedURLException: Illegal character in URL (Illegal character in URL)
   [error]       Caught java.io.IOException: Server returned HTTP response code: 500 for URL: http://repo.youdevise.com/nexus/content/groups/public/org/jboss/spec/javax/ws/rs/jboss-jaxrs-api_2.0_spec/1.0.0.Final%0A%20%20%20%20%20%20%20%20/jboss-jaxrs-api_2.0_spec-1.0.0.Final%0A%20%20%20%20%20%20%20%20.pom (Server returned HTTP response code: 500 for URL: http://repo.youdevise.com/nexus/content/groups/public/org/jboss/spec/javax/ws/rs/jboss-jaxrs-api_2.0_spec/1.0.0.Final%0A%20%20%20%20%20%20%20%20/jboss-jaxrs-api_2.0_spec-1.0.0.Final%0A%20%20%20%20%20%20%20%20.pom)
   [error]     not found: /Users/broberts/.ivy2/local/org.jboss.spec.javax.ws.rs/jboss-jaxrs-api_2.0_spec/1.0.0.Final
   [error]         /ivys/ivy.xml
   [error] Total time: 2 s, completed Dec 8, 2016 8:35:37 AM
