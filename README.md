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
	```

* 이미지 등록 확인 ( isRegistered )
	> 해당 이미지가 등록되어 있는지 확인합니다.
	> Return if image is alreardy registered.
	```java
	ImageLoader.isRegistered(String imageName)
	```

* 이미지 등록 확인 ( getImageList )
	> 등록된 이미지 리스트를 불러옵니다.
	> Get name list of registered images.
	```java
	ImageLoader.getImageList()
	```

* 이미지 등록 확인 ( getImageData )
	> 등록된 이미지의 RGB 데이터를 불러옵니다.
	> get RGB data of image.
	```java
	ImageLoader.getImageData(String imageName)
	```
