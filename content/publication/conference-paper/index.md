---
title: 'Driver drowsiness detection system through facial expression using CNN'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Rajesvary Rajoo
  - Patricia Jayshree Jacob

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-04-10T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Malaysian Journal of Computing*
publication_short: In *MJOC*

abstract: Driver drowsiness or fatigue is a significant factor that causes road accidents each year and considerably affects road safety. According to the World Health Organization (WHO), drowsy driving may contribute to approximately 6% of fatal and severe road accidents. To overcome this problem, we present a state-of-the-art, real-time drowsiness detection system, which exploits innovative deep-learning techniques to evaluate facial expressions. Our system analyzes not just the driver's eyes, mouth, and head rotation pose with front angles but also left and right yaw angles up to 90° to ensure the driver's safety. We gathered a dataset from public stock image websites, and manual image captures to develop the system. After processing the dataset, we extracted a wide range of features, which we fed into a deep convolutional neural network (CNN) algorithm. Specifically, we employed three different CNN algorithms which are EfficientDet D0, SSD MobileNet V2, and SSD ResNet50 V1, to classify the driver's drowsiness status using the facial key attributes in real time. Our results show that the SSD ResNet50 V1 model exhibited the highest accuracy and consistency in detecting driver drowsiness, underscoring the potential of our innovative system in promoting road safety. Our future work will focus on fine-tuning the approach to enhance its accuracy and performance.

# Summary. An optional shortened abstract.
summary: Driver fatigue significantly impacts road safety, causing numerous accidents. We developed a real-time detection system using deep learning to analyze facial cues and ensure safety, with promising results from convolutional neural networks (CNN) algorithms, particularly SSD ResNet50 V1.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://mjoc.uitm.edu.my/main/images/journal/vol8-1-2023/9_DRIVER_DROWSINESS_DETECTION_SYSTEM_THROUGH_FACIAL_EXPRESSION_USING_CONVOLUTIONAL_NEURAL_NETWORKS_CNN.pdf'
url_code: 'https://github.com/NipaDasGupta/DrowsinessDetection'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**appen**](https://s41256.pcdn.co/wp-content/uploads/2022/10/221019_DriverAwareness_2_Blog.jpg.webp)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
