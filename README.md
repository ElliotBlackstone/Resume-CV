**Elliot Blackstone, Ph.D.**  
Ann Arbor, Michigan | US citizen | [Email](mailto:eblackst2@gmail.com) | [LinkedIn](http://www.linkedin.com/in/elliot-blackstone-eblackstone) | [GitHub](https://github.com/ElliotBlackstone)

**SUMMARY** 

Machine learning engineer with a Ph.D. in mathematics, building computer vision and tabular ML systems in PyTorch and scikit-learn. Experience developing custom object detection models, optimizing inference with ONNX/INT8 quantization, and deploying ML applications from training through production-style demos.

**SKILLS & CERTIFICATIONS**

* Programming & Tools: Python (NumPy, pandas, scikit-learn, matplotlib), C++, LaTeX, Jupyter, Git, Mathematica, Linux  
* ML & Computer Vision: PyTorch, torchvision, CUDA, CNNs, ONNX, Quantization, OpenCV  
* Tabular ML: XGBoost, LightGBM, CatBoost, Random Forest, linear/logistic regression, Optuna, SHAP, cross validation  
* Deployment & MLOps: Docker, FastAPI, Google Cloud Platform (Cloud Run), ONNX Runtime
* Certifications/Awards:  Erdős Institute [Data Science Boot Camp](https://www.erdosinstitute.org/certificates/spring-2025/data-science-boot-camp/elliot-blackstone/eaeaf444-44be-444f-a1aa-6d15d4e347ba), UofM [Honored Instructor](https://housing.umich.edu/michigan-housing-honored-instructors/), UCF [best dissertation award](https://sciences.ucf.edu/math/graduate/alumni/)

**SELECTED PROJECTS** 

**Automotive Object Detection**  \[[Online Demo](https://ssd-demo-app-884945419812.us-central1.run.app/)\] \[[GitHub](https://github.com/ElliotBlackstone/automotive-ssd-object-detection)\]                                         	  	                               **2025-2026** 

* Built a from-scratch Single Shot Detector in PyTorch for automotive object detection on a 30k-image dataset with 195k labeled bounding boxes; improved data augmentation, sampling, and training pipeline to reach 0.54 mAP@0.50 on the test set.
* Re-architected the project into a modular training and inference pipeline and eliminated bottlenecks through profiling, mixed precision, batched target matching, batched NMS, and DataLoader tuning, reducing end-to-end training time from **50h to 25h**.
* Developed gen-nms-package, a standalone PyTorch C++/CUDA extension for GIoU, DIoU, and CIoU non-maximum suppression on CPU and GPU, enabling compiled postprocessing beyond the standard torchvision NMS operators.
* Built optimization and deployment stack around the model, including ONNX export, PyTorch/ONNX Runtime parity testing, static INT8 post-training quantization, benchmarking, and both browser-based and local real-time webcam/video inference.

**Predicting Calorie Expenditure \-** *The Erdős Institute*  \[[LINK](https://www.erdosinstitute.org/certificates/summer-2025/data-science-boot-camp/elliot-blackstone/008dc3e4-1c7b-49e6-848b-bab3d772ed54)\] \[[GitHub](https://github.com/ElliotBlackstone/S25_Predict_Calories)\]                                        	  	**2025** 

* Built a supervised learning pipeline to predict workout calorie expenditure from a 750k-row tabular dataset, with log-transform and engineered features, training and tuning linear, GAM, XGBoost, LightGBM, CatBoost, ensemble, and AutoGluon models using Optuna and SHAP, and achieving **4th place out of 4,318 teams** in a Kaggle competition.

**Forecasting Inventory Demand \-** *The Erdős Institute*  \[[LINK](https://www.erdosinstitute.org/certificates/spring-2025/data-science-boot-camp/elliot-blackstone/eaeaf444-44be-444f-a1aa-6d15d4e347ba)\] \[[GitHub](https://github.com/ElliotBlackstone/EWinter25_Product_Inventory)\]                                                       **2025** 

* Engineered an inventory demand prediction model for the Kaggle Grupo Bimbo competition on a 75 million row dataset, training LightGBM models with client/product aggregate features and adjusted demand from the previous 3 weeks to handle sparse data and cold-start scenarios and improve inventory-demand forecasts.

**WORK EXPERIENCE**

**University of Michigan:** Ann Arbor, MI			             		                 	                **2021 \- 2025**  
*Postdoctoral Assistant Professor and James Van Loo Postdoctoral Fellow*

* Implemented numerical simulations and data analysis pipelines in Mathematica to study PDE dynamics and visualize emergent patterns. This work led to the publication of four [papers](https://scholar.google.com/citations?user=fQ1-hU4AAAAJ&hl=en) and was presented at international conferences.  
* Developed course material and taught over 300 students topics such as probability theory, calculus, linear algebra, polynomial regression, and mathematical modeling. Won a teaching award and was named UofM [Honored Instructor](https://housing.umich.edu/michigan-housing-honored-instructors/).

**KTH Royal Institute of Technology:** Stockholm, Sweden		     	      				    **2019 \- 2021**  
*Postdoctoral Researcher*

* Conducted full-time research in random matrix theory. Performed numerical analysis to verify asymptotic convergence rates, ensuring theoretical models aligned with computational outputs. This work led to the publication of four [papers](https://scholar.google.com/citations?user=fQ1-hU4AAAAJ&hl=en).

**University of Central Florida:** Orlando, FL			             			         		    **2012 \- 2019**  
*Research & Teaching Assistant*

* Co-authored two [papers](https://scholar.google.com/citations?user=fQ1-hU4AAAAJ&hl=en) as part of PhD research that advanced the mathematical foundations of inverse problems and tomographic reconstruction; core techniques in signal processing and computational imaging. Won [best dissertation award](https://sciences.ucf.edu/math/graduate/alumni/).  
* Developed course material and taught over 600 students between 12 calculus courses, two differential equations courses, and two linear algebra courses. Topics taught include linear regression, singular value decomposition, and multivariable calculus.

**EDUCATION**  
**University of Central Florida,** *Ph.D. Mathematics*		        	        	                         	                  	                 **2019**  
**University of Central Florida,** *M.S. Mathematics*		        	        	                         	                  	                 **2014**  
**Penn State Erie,** *B.S. Mathematics (Statistics Minor)*    	        	        	                         	                  		    	    **2011**
