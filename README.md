# Wildlife-infrared-tracking-camera

**The project is made when participating in a "creative AI design challenge". Most of the projects are imaginative and have not considered the feasibility**

Your advice are most welcome

中文文档在下方

--------------------

AI infrared wildlife tracking stealth camera robot

### Design background:

The global forest resources are very rich. There are a lot of wild animals living in the forests. What changes have taken place in the diversity and population number of wild animals, and what factors affect or potentially affect the changes, we are not clear, which brings difficulties to the protection of wildlife resources. At present, the development of infrared camera technology helps researchers to obtain the image data of precious wild animals in the deep forest. However, the opportunity of shooting is limited. Compared with the vast forest area, the number of samples placed manually by the existing equipment is very few, and it is a great test for researchers because of the danger of deep forest. If more human resources are invested into the original forest, the garbage generated will pollute the natural ecological environment; human odor will disturb the natural rules, and will affect the health of wild animals. The infrared camera placed manually can only be placed in a fixed position, and the working frequency can not be too high, so it has great limitations on observation and research. Due to the variety and quantity of wild animals, different habits, huge amount of image data information, artificial management system analysis and processing work is slow. Looking forward to the future, we need such an artificial intelligence system, which can not only capture photos in real time, but also track and shoot quietly. It also has strong background support for network data analysis. It can register species, record individuals, and quickly analyze every wild animal tracked, without damaging the natural ecological environment and affecting the life of animals The living law is helpful to the comparative study of multiple groups in time and space, realizing the network and visualization of monitoring data, promoting the scientific research and protection of wild animals, and establishing and stabilizing the online monitoring system of wild animals.

### Main functions:

This is a collection of wildlife image data tracking acquisition, storage, analysis and information exchange system, through the AI infrared automatic tracking camera robot system to capture high-definition pictures or smooth video to obtain wildlife graphics and image data, and through these wildlife images to analyze the species composition, distribution, population number, behavior, habitat of wild animals It provides important scientific basis for wildlife protection and management and resource utilization.

1.  Map setting longitude and latitude service area, mobile detection, real-time continuous shooting, tracking video.

2.  It has strong anti-interference ability, high image cable and fast capture speed. It can set the number of follow-up shots and the shooting time according to the situation.

3.  Deep AI algorithm can automatically identify animals, classify and retrieve objects, track records or create new data samples.

4.  The image / video and analysis data are transmitted to the background system in real time.

5.  No need to add power supply module, solar power supply, sustainable standby monitoring.

6.  Made of high-tech materials, the color of the outer body can be changed according to the surrounding environment. Like a spider, it is retractable and highly sensitive. It can walk, fly or hide in silence.

7.  Cold and heat-resistant, safe, waterproof and shockproof, suitable for all kinds of natural environment.


This is a system for tracking, acquiring, storing and analyzing wildlife image data and exchanging information,
It mainly uses infrared automatic tracking camera robot to take pictures or videos to obtain the image data of wild animals,
These images can be used to analyze the species composition, distribution, population number, behavior, habitat, food source, breeding offspring and living environment of wild animals,

So as to provide important scientific basis for wildlife protection and management and resource utilization.

What kind of problem to solve: better help researchers to research and protect endangered wildlife

Concept: a system for tracking, acquiring, storing and analyzing wildlife image data and exchanging information

Difficulty: because some animals have a very keen sense of hearing, moving noise needs to have no impact on the life of wild animals

Application: after the detection of animals, apply image recognition technology / automatic road recognition and tracking during tracking / big data calculation and statistics of animal data and relationship

Principle of image recognition: identify according to the classification in the database, check whether there is an image with the same or similar characteristics as the image, so as to identify the image. That is, to identify the image by classification and extraction of important features.

The use of artificial intelligence in data transmission, image recognition and other aspects of saving time, but also more convenient, can also reduce the risk of human beings to the wild environment and the wild environment.

Ideal: make this camera smaller, move faster, capture information more accurately

Through the identification of machines, like us, we can give each endangered wildlife an "ID card" to record their growth and change.

python code

This program mainly uses the CV2lib to detect objects. Assuming that there are two images collected at different times, the simplest way to detect motion is to calculate the image difference. In other words, by subtracting the brightness value, the change or movement can be obtained; if there is no movement, the subtraction result will be 0; but if the target in the image moves, their image pixel brightness value will change, and the subtraction result is a non-zero value, they will take photos and store the photos in the computer.


-----------------------
中文文档

AI红外野生动物追踪隐形摄像机器人

设计背景：

全球森林资源十分丰富，在森林中生活着很多野生动物，野生动物多样性和种群数量究竟发生哪些变化，以及哪些因素影响或潜在影响其变化我们很不清楚，给野生动物资源保护带来困难。目前，红外相机技术的发展帮助研究人员在森林深处可以获取珍贵野生动物的图像数据。但拍摄的机会稍纵限逝，现有的设备人工布放的样区样点数与广阔的森林面积相比少之甚少，而且因森林深处的危险性着实对研究人员是一重大考验。如果投入更多的人力进入原始森林，那么产生的垃圾又会污染自然生态环境；人类的气味将扰乱大自然规则，更会影响野生动物的健康。人工放置的红外相机只能放在固定位置，收取的工作频率不能太高，只能守株待兔，对观察研究有很大的局限性。 因野生动物种类及数量繁多，习性不一，图像数据信息量庞大，人工管理系统分析处理工作缓慢。瞻望未来，我们需要这样一个人工智能系统，不但能实时抓取拍照，最主要是它可以悄无声息的追踪拍摄，且有强大的网络数据分析后台支持，对追踪到的每一个野生动物可以进行物种登记、个体记录、快速分析等等，又不会破坏自然生态环境，不会影响动物的生活规律，有助于多个类群在时间和空间上的比较研究，可实现监测数据的网络化和可视化，可以更好的推动野生动物的科学研究和保护工作，建立和稳定野生动物联网监测体系。




主要功能：

这是一个集野生动物图像数据的追踪获取、存贮、分析和信息交流的系统，通过AI红外自动追踪摄像机器人系统拍摄高清晰度的图片或流畅的视频来获取野生动物图形图像数据，并通过这些野生动物图像来分析野生动物的物种组成、分布、种群数量、行为、栖息地、食物来源、繁衍后代和生存环境等重要信息，从而为野生动物保护管理和资源利用提供重要科学依据。

1、地图设定经纬度服务区域，移动侦测、实时连拍、跟踪录像。

2、抗干扰能力强，拍摄像索高，抓拍速度快，可根据情况自行判断设置跟拍数量和摄像时长 。

3、深度AI算法自动识别动物，目标分类检索，追踪记录或新建数据样本。

4、实时直接将图像/视频及分析数据传输发送到后台系统。

5、无需添加供电模块，太阳能供电，可持续待机监测。

6、采用高科技材料制成，外体颜色可以根据周围环境而自行改变。形似蜘蛛，可伸缩、高灵敏度，可无声行走、飞行或隐藏。

7、耐寒耐热、安全防水防震、适用各种自然环境。



这是一个通过对野生动物图像数据进行追踪获取、存贮分析和信息交流的系统，
主要是通过红外自动追踪摄像机器人拍摄图片或视频来获取野生动物的图像数据，
并通过这些图像来分析野生动物的物种组成、分布、种群数量、行为、栖息地、食物来源、繁衍后代和生存环境等重要信息，
从而为野生动物保护管理和资源利用提供重要科学依据。


解决什么样的问题：更好的帮助科研人员对濒危野生动物的研究和保护

理念： 通过对野生动物图像数据进行追踪获取、存贮分析和信息交流的系统

困难处：因为一些动物的听觉非常敏锐，所以移动时的噪音需要做到对野生动物的生活毫无影响

应用：检测到动物后，应用图像识别技术  /  跟踪时进行自动道路识别和跟踪  /  对动物的数据和关系进行大数据计算并统计……

图像识别原理：根据数据库中已经分好的类别进行识别,查看是否有与该图像具有相同或类似特征的图像,从而识别出该图像.也就是通过分类并提取重要特征来识别图像。

使用人工智能在数据传输，图像识别等方面都节省了时间，也更加方便，也可以减少人类对野外环境坏和野外化境的人类的危险。

理想：让这个摄像机体积更小，移动速度更快，抓取信息更加精准……

可以通过机器的识别，像我们人类一样，给每一个濒危野生动物一个“身份证”，以记录它们一身的生长变化。


python 代码：

这个程序使用主要使用了cv2库，对物体进行检测，假设有两帧不同时间采集的图像，检测运动的最简单方法就是计算图像差值。也就是说，通过把亮度值相减可以得到变化或者运动；如果没有发生运动，相减的结果就是0；但如果图像中的目标作出的运动，他们的图像像素亮度值就会发生变化，相减结果是一个非0的值，就会进行拍照，将照片存储到电脑中。







