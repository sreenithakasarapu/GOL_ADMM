# GOL_ADMM

In autonomous and self-driving vehicles, visual perception of the driving environment plays a key role. Vehicles rely on
machine learning (ML) techniques such as deep neural networks (DNNs), which are extensively trained on manually annotated
databases to achieve this goal. However, the availability of training data that can represent different environmental conditions can be
limited. Furthermore, as different driving terrains require different decisions by the driver, it is tedious and impractical to design a
database with all possible scenarios. This work proposes a semi-parametric approach that bypasses the manual annotation required to
train vehicle perception systems in autonomous and self-driving vehicles. We present a novel “Performance and Environment-aware
Advanced Driving Assistance Systems” which employs one-shot learning for efficient data generation using user action and response
in addition to the synthetic traffic data generated as Pareto optimal solutions from one-shot objects using a set of generalization
functions. Adapting to the driving environments through such optimization adds more robustness and safety features to autonomous
driving. We evaluate the proposed framework on environment perception challenges encountered in autonomous driving assistance
systems. To accelerate the learning and adapt in real-time to perceived data, a novel deep learning-based Alternating Direction Method
of Multipliers (dlADMM) algorithm is introduced to improve the convergence capabilities of regular machine learning models. This
methodology optimizes the training process and makes applying the machine learning model to real-world problems more feasible. We
evaluated the proposed technique on AlexNet and MobileNetv2 networks and achieved more than 18× speedup. By making the
proposed technique behavior-aware we observed performance of upto 99% while detecting traffic signals.
