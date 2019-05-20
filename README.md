# RaptorEngine
Android,IOS and Web applications under Raptor Engine.

# Releases
 1. Alpha - The war/jar/apk from the *Alpha branch* created should contain ads if applicable.
 2. Beta - The war/jar/apk from the *Beta branch*, after the alpha release has been done.
 3. Production - The war/jar/apk from the *shakeout branch*, after the beta release has been peer reviewed.

# Names
 1. Master - The branch into which the final code will be pushed *After the app is release and the peers feel that the app is stable*.
 2. Shakeout - The branch from which the *Production* release war/jar/apk will be taken.
 3. Beta - The branch from which the *Beta* release war/jar/apk will be taken.
 4. Alpha - The branch from which the *Alpha* release war/jar/apk will be taken.
 
 # Versions -> 1.0.0.0.0
 *From right to left* , *All Apks must be COPIED,SAVED AND NAMED WITH THE PROPER VERSION NUMBER AND DATE*
 1. For minor code changes from the original plan and bug fixes.
 2. For any UI changes or upgrades.
 3. For any Code functionality changes or upgrades.
 4. UI and Code changes together or upgrades.
 5. For any overhaul performed or complete UI revamp.
 
# Nomenclature
 1. branched must be named appropriately with the version number of the application at the end.

# Deletions
 1. Any and all branches Except the Master and shakeout can be deleted.

# Pulls
 1. Any code pull must be done from the Beta branch only.
 2. There should not be any code changes done directly on the Beta branch.
 3. The code should never be pulled from the shakeout branch.

# Pushes
 1. A branch must be created if:
   1.1 A new version of the application is being created.
   1.2 A new person will be working on the application.
   1.3 Major code changes or fixes.
 2. Any code push must be done from the respected branch to the Beta branch only and a pull requested must be created which will be      verified my all peers.
 3. The code will be merged with the Beta branch, only after a thorough review has been done and the code is accepted by all the          peers.
 4. The code should never be pushed to the shakeout branch. 
  
# Merges
 1. Any and all code merges from an individual branch must be peer reviewed before merger into Beta.
 2. Shakeout and Beta merger will be done after an alpha or beta release ie., after a thorough code inspection and beta test.
 3. Master and Shakeout merger should only be done after the production release of the application.
 4. It is the responsibility of the person inspects,reviews and verifies the code from an individual branch to accept the pull request and     merge the code with the *Beta branch.*
