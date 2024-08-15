# Why is Data Definition Hard?

Defining what data to use can be complex.

**Iguana Labeling Example**

 - Imagine a picture with one iguana in the front and another on the back;
 - This picture is sent to three labelers for bounding box annotations;
 - **Variability in Labeling:**
    - **Labeler 1:** correctly identifies one or two iguanas;
    - **Labeler 2:** provides a different bounding box but still identifies the same number of iguanas;
    - **Labeler 3:** offers a generic bounding box.

**Phone Defect Detection Example**

 - Imagine a picture of a phone with a big scratch and one small pit mark;
 - This picture is also sent to three labelers for bounding box annotations;
 - **Variability in Labeling:**
    - **Labeler 1:** identifies a scratch as the only defect;
    - **Labeler 2:** recognizes two defects, including a small pit mark;
    - **Labeler 3:** offers a generic bounding box.

# Importance of Consistent Labeling

 - Mixing labeling conventions (e.g., using all three styles) can confuses the learning algorithm;
 - Clear labeling instructions can reduce noise and inconsistency, enhancing algorithm performance;
 - Questions to consider when defining data:
    - **Input (X) Considerations:** Evaluate the quality of input data (e.g., image clarity, audio quality) to ensure it's suitable for labeling;
    - **Target Label (Y) Definition:** Establishing how to ensure consistent labeling across instances is crucial.
