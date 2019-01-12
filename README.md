# Visual Studio Code Tools for AI
AI를 위한 비주얼스튜디오 코드 툴즈(Visual Studio Code Tools for AI, 이하 영문 Visual Studio Code Tools for AI로 사용)는 딥러닝/AI 솔루션들을 빌드, 테슽, 및 배치(deploy)하기 위한 부가기능(익스텐션)입니다. 강력한 실험 능력을 갖춘 애저 머신러닝에 중단없이(seamlessly) 통합하기 위한 것으로서 데이터 전처리 및 모델 훈련 등을 포함해서 각기 다른 연산 목적에 투명하게 적용하기 위한 것입니다. 게다가 맞춤형 측정과 운영 히스토리 추적, 데이터 사이언스 재현성과 검사 등을 지원합니다. 산업에서 협조가 가능하며 다른 사람들과 프로젝트를 보안화한 상태로 작업이 가능하게 도와 줍니다.

[Microsoft Cognitive Toolkit (CNTK)](http://www.microsoft.com/en-us/cognitive-toolkit), [Google TensorFlow](https://www.tensorflow.org)또는 최신 다른 딥러닝 프레임워크드을 사용해서 딥러닝 시작하기.

## Quick Links

**시작하기**

- [설치하기](/docs/installation.md)
- [개발 환경 준비](/docs/prepare-localmachine.md)
- [딥러닝 샘플 레시피](https://github.com/Microsoft/samples-for-ai)
- [자주하는 질의 응답](/docs/faq.md)

**빠른 시작**

- [Tensorflow + Python](/docs/tensorflow-local.md)
- [샘플갤러리에서 AI 프로젝트 생성하기](/docs/quickstart-00-project-from-azuremachinelearning-gallery.md)
- [클라우드에서 모델 훈련하기](/docs/quickstart-01-submitting-training-jobs.md)
- [업무 히스토리 관리](/docs/quickstart-02-job-view.md)
- [스토리지 관리](/docs/quickstart-03-storage-explorer.md)
- [Azure Batch AI에서 모델 훈련하기](/docs/quickstart-04-train-azure-batchai.md) 
- [PAI에서 모델 훈련하기](/docs/quickstart-05-pai.md) 

## 지원 OS
이 익스텐션은 아래의 64비트 OS를 지원합니다:
- Windows
- macOS

## Features

### Develop deep learning and AI solutions across Windows and MacOS
VS Code Tools for AI는 크로스 플랫폼 익스텐션으로 [Microsoft Cognitive Toolkit (CNTK)](http://www.microsoft.com/en-us/cognitive-toolkit), [Google TensorFlow](https://www.tensorflow.org)와 그 밖의 딥러닝 프레임워크들을 지원합니다

Because it's an IDE we've enabled familiar code editor features like syntax highlighting, IntelliSense (auto-completion) and text auto formatting. You can interactively test your deep learning application in your local environment using step-through debugging on local variables and models. 

![deep learning ide](/docs/media/deeplearning-ide.png)

### Find and share examples via the gallery  
Visual Studio Code Tools for AI is integrated with Azure Machine Learning to make it easy to browse through a gallery of sample experiments using CNTK, TensorFlow, MMLSpark and more. This makes it easy to learn and share with others. 

[Learn more about creating projects from the sample gallery](/docs/quickstart-00-project-from-azuremachinelearning-gallery.md)

![sample explorer](/docs/media/aml-samples/sampleexplorer.png)

### Scale out deep learning model training and/or inferencing to the cloud
This extension makes it easy to train models on your local computer or you can submit jobs to the cloud by using our integration with Azure Machine Learning. You can submit jobs to different compute targets like Spark clusters, Azure GPU virtual machines and more. Besides, [Azure Batch](https://azure.microsoft.com/en-us/services/batch/) and [Open Platform for AI (PAI)](https://github.com/Microsoft/pai) are also supported.

[Learn more about training models in the cloud](/docs/quickstart-01-submitting-training-jobs.md)
 
![submit job](/docs/media/job/submit-target.png)

### View recent job performance and details
Once the jobs are submitted, you can list the jobs, check the job details and download models, logs, etc. from the run history.

[Learn more about job history](/docs/quickstart-02-job-view.md)

![Job View](/docs/media/job/job-view.png)

### Manage storage on compute targets
The extension provides a storage explorer which enables you to manage your files on remote machines, Azure Batch clusters, PAI clusters, etc. You can create/delete folders, upload/download files within the VS Code easily.

[Learn more about storage explorer](/docs/quickstart-03-storage-explorer.md)

![Storage View](/docs/media/storage/StorageExplorer.png)

## Commands
The extension provides several commands in the Command Palette for working with deep learning and machine learning:
- **AI: Azure - Login**:  Login to Azure to access resources used by Azure ML / Azure BatchAI.
- **AI: Azure - Set Subscription**:  Set your Azure Subscription to use for Azure ML / Azure BatchAI
- **AI: Open Azure ML Sample Explorer**: Quickly get started with machine learning and deep learning experimentation by downloading sample projects you can run and modify to meet your needs 
- **AI: Azure ML - Open Terminal**: Open Azure CLI terminal to access full Azure feature set
- **AI: Add Platform Configuration**: Configure compute target (remote VM, BatchAI cluster, PAI cluster) used for training job. **For BatchAI, this command creates a cluster in Azure**.
- **AI: Edit Platform Configuration**: Modify compute target settings.
- **AI: Remove Platform Configuration**: Remove a compute target configuration. **For BatchAI, this command removes the cluster in Azure**.
- **AI: Submit Job**: Submit a training job to remote Linux VMs, BatchAI clusters, PAI clusters, etc.
- **AI: Edit Job Properties**: Modify job settings.
- **AI: List Jobs**: View list of recent jobs you've submitted and their details
- **AI: Open Storage Explorer**: View and manage storage on remote compute targets.

## Support
Support for this extension is provided on our [GitHub Issue Tracker](http://github.com/Microsoft/vscode-tools-for-ai/issues). You can submit a bug report, a feature suggestion or participate in discussions.

## Code of Conduct
This project has adopted the [Microsoft Open Source Code of Conduct]. For more information see the [Code of Conduct FAQ] or contact [opencode@microsoft.com] with any additional questions or comments.

## Privacy Statement
The [Microsoft Enterprise and Developer Privacy Statement] describes the privacy statement of this software.

## License
This extension is subject to the terms of the [End User License Agreement]. 

[Microsoft Enterprise and Developer Privacy Statement]:https://go.microsoft.com/fwlink/?LinkId=786907&lang=en7
[Microsoft Open Source Code of Conduct]:https://opensource.microsoft.com/codeofconduct/
[Code of Conduct FAQ]:https://opensource.microsoft.com/codeofconduct/faq/
[opencode@microsoft.com]:mailto:opencode@microsoft.com
[End User License Agreement]:https://www.visualstudio.com/license-terms/mlt552233/
