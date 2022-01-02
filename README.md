# supply-chain-maslow
Maslow’s Hierarchy of Needs for Supply Chains

This started from a Twitter thread
https://twitter.com/joshbressers/status/1477366321436319745


```
                                  
                                 / \
                                /   \
                               /     \
                              /       \
                             /         \
                            /           \
                           /-------------\
                          /               \
                         / Reproducibility \
                        /                   \
                       /---------------------\
                      /                       \
                     /      Updatability       \
                    /                           \
                   /-----------------------------\
                  /                               \
                 /            Trusted              \
                /                                   \
               /-------------------------------------\
              /                                       \
             /      Free of known vulnerabilities      \
            /                                           \
           /---------------------------------------------\
          /                                               \
         /                 What's in it?                   \
        /                                                   \
        .----------------------------------------------------.
```


## Reproducibility
 * Reproducible builds
 * Independent verification of builds
## Can it be updated
 * Update components
 * Update the application
 * Update the operating system
## Can it be trusted?
 * Is it signed?
 * Can we verify the signature?
 * How is the build system being secured?
 * Is the source of the project doing verification?
 * Who is watching for vulnerabilities and bugs?
 * Who is is the project?
   * Who manages it?
   * How often is it updated?
   * Are the managers easy to contact?
   * Are the managers responsive to bug reports?
## Is it free of major bugs and vulnerabilities?
 * Are there unsupported packages?
   * Are the transitive dependencies updated?
 * Do the old packages contain dangerous bugs?
 * How old?
 * What is the attack surface
## What's in it?
 * SBOM
   * Including transitive dependencies
 * Are there any duplicate or unnecessary components?
