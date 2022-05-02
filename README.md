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
                 /           Confidence            \
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
 * Reproducible content
 * Independent verification of content
## Trusting updates
 * Update components
 * Update the application
 * Update the operating system
## Artifact confidence
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
 * How old are the components?
 * What is the attack surface
## What's in it?
 * SBOM
   * Including transitive dependencies
 * Are there any duplicate or unnecessary components?



# Notes
https://twitter.com/p_millerd/status/1509323819600732160
