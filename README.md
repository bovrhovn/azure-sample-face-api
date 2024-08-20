# Azure Cognitive Services Face API - information and samples

The Azure AI Face service provides AI algorithms that detect, recognize, and analyze human faces in images. Facial
recognition software is important in many different scenarios, such as identification, touchless access control, and
face blurring for privacy. The Face service provides
a [REST API](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/identity-api-reference) for working
with faces (and SDK support for server side
or [client side](https://orange-forest-0ea70d510.5.azurestaticapps.net/)), and it can be used in a variety
of applications, including security, retail, and automotive.

## Face API features

The Face API provides a variety of features for working with faces in images. These features include:

1. **Face detection and analysis**

- Detect human faces and returns the rectangle coordinates of their locations. It can detect also faces from video
  stream feed – more here.
- Optionally, it can extract a set of face-related attributes, such as head pose, age, facial hair and glasses. For
  example, you can advise users to take off their sunglasses if they’re wearing glasses. More here.

2. **Liveness detection** - Face Liveness detection can be used to determine if a face in an input video stream
   is real (live) or fake (spoof). This is a crucial building block in a biometric authentication system to prevent
   spoofing attacks from imposters trying to gain access to the system using a photograph, video, mask, or other means
   to impersonate another person. Our liveness detection solution meets iBeta Level 1 and 2 ISO/IEC 30107-3 compliance.

3. **Face recognition**

- Identification – one to many recognition. For example, granting access to a certain group of people or
  verifying the user of a device.
- Verification - Verification is also a "one-to-one" matching of a face in an image to a single face
  from a secure repository or photo to verify that they're the same individual.
- Find similar faces - he Find Similar operation does face matching between a target face and a set of
  candidate faces, finding a smaller set of faces that look similar to the target face. This is useful for doing a face
  search by image.
- Group faces - The Group operation divides a set of unknown faces into several smaller groups based on
  similarity.

You can check the API
structure [here](https://learn.microsoft.com/en-us/rest/api/face/operation-groups?view=rest-face-v1.2-preview.1).

## Demos

Example demos are available in the [Demos](Demos) folder. These demos show how to use the Face API to perform various
tasks.

## Calculations

The Face API can be used to perform a variety of calculations on faces in images. These calculations can be used to
understand
how much will the use of services cost.

Calculations are available in the [Calculations](Calculations) folder.

# Additional resources

- [Face API documentation](https://learn.microsoft.com/en-us/azure/cognitive-services/face/)
- [Face API pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/face-api/)
- [Face API SDKs](https://learn.microsoft.com/en-us/azure/cognitive-services/face/overview)