Image Filtering App using Linear Algebra (MATLAB)

Welcome to Image Filtering with Linear Algebra, a dynamic MATLAB-based application that demonstrates how fundamental linear algebra operations can power real-world image processing techniques — without relying on MATLAB's built-in image functions.

Project Overview
This project simulates an image filtering and transformation tool (like a mini Photoshop) where all operations such as cropping, contrast adjustment, rotation, flipping, scaling, and cartoon/watercolor effects are implemented using pure linear algebra (matrix multiplication, affine transforms, coordinate systems).

All operations run via interactive GUI controls like sliders and click-to-select regions.

Core Linear Algebra Concepts Used
Operation	        Concept Used
Cropping	        Matrix selection via row/column selector matrices
Contrast	        Affine transformation: I' = αI + β
Rotation	        Rotation matrices with coordinate translation
Flipping	        Reflection matrices over X/Y axis
Scaling	          2×2 Scaling matrix + inverse mapping
Cartoon Effect	  Color quantization (K-means), matrix reshaping
Watercolor Effect	Downscaling/upsampling, bilateral filtering, edge subtraction

Features Implemented
✅ Image Cropping (matrix-based, not imcrop)

✅ Contrast & Brightness adjustment (via affine maps)

✅ Rotation using matrix transformation with canvas resizing

✅ Flipping (horizontal & vertical reflections)

✅ Scaling / Zooming (interactive sliders, matrix resampling)

✅ Cartoon Effect (color quantization + edge subtraction)

✅ Watercolor Effect (smoothening + artistic blending)

✅ Real-time GUI sliders and user inputs for live previews


📚 Learnings
“This project proves that powerful visual transformations can be implemented using only matrix algebra — reinforcing the bridge between theory (linear algebra) and practice (image processing).”

🤝 Contributors
👩‍💻 Sourav Kumar Verma — Undergrad Student
👩‍💻 Nitin — Undergrad Student
👩‍💻 Harshit Paliwal — Undergrad Student

🎓 Under the guidance of Shobha Bagai Mam
