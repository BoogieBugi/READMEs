# B_ImageToParticle
### 이미지 파일을 통해 파티클을 생성하는 라이브러리
### Create Particle Shapes by Image.

## Usages
### ImageLoader.java
> 이미지 파일을 관리하는 클래스입니다. 
> Management image files.
* 임포트 ( import )
	```java
	import com.bugi.b_imagetoparticle.ImageLoader
	```
* 이미지 등록 ( registerImage )
	> 리소스 파일에서 이미지를 불러와 등록합니다.
	> Register data of image in plugin's resources folder.
	```java
	ImageLoader.registerImage(Plugin plugin, String imageName, String fileName)
	```
* 이미지 등록 취소 ( unregisterImage )
	> 등록되어 있는 이미지 데이터를 제거합니다,
	> Unregister data of image.
	```java
	ImageLoader.unregisterImage(String imageName)
