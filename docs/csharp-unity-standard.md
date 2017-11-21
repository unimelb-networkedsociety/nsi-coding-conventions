# Unity Project NSI Standard:
1. In your Unity project, create the following folders:
    - Prefabs
    - Scenes
    - ThirdPartyPackages (All the external assets you imported)
    - Materials
    - Scripts
    - Audios (If you have audio in your projects)
    - Animations (If you have animations in your projects)


2. Your C# Script must follow the style as below:

        // Author:
        // Date:
        // Purpose: (Purpose of this script)

        namespace NSI.ProjectName {
            class SomeClass {
                #region Public Variables
                //Your code
                #endregion

                #region Private Variables
                //Your code
                #endregion

                #region MonoBehaviour Callbacks 
                //Your code such as void Start() {}, void Update() {} related to MonoBehaviours.
                #endregion

                #region Public Methods
                //Your code
                #endregion

                #region Private Methods
                //Your code
                #endregion
            }
        }