# XDTesting Create Directory
This action is able create a directory structure in the Github repository useful for the testing of ontology fragments based on the [eXtreme Design](extremedesign.info) methodology. The created directories are: 1) CompetencyQuestionVerificationTest, 2) InferenceVerificationTest, 3) ErrorProvocationTest, 4) TestDocumentation, 5) TestingUserInput, with respective subfolders and files. The created file is ontology.owl. 

The directories and files are later pulled to the repository via a Pull Request that needs to be confirmed from the ontology engineer. 


# Usage 
Add the following entry to your Github workflow YAML file:

```
steps:
  - name: XDTesting Create Test Directory
    uses: FiorelaCiroku/XDTesting-CreateDirectory@v1.0.23
  
```
