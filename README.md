# Decode large images in android using tiles

## Features
 * df

## Usage

``` java
	try {
			// String path = getIntent().getData().toString();
			mTextureView = new TiledImageView(this);
			// mTextureView.setTileSource(new BitmapRegionTileSource(Environment
			// .getExternalStorageDirectory().getAbsolutePath()
			// + "/4167.jpg"));

			mTextureView.setTileSource(new BitmapRegionTileSource(getAssets()
					.open("abc.jpg")));

			setContentView(mTextureView);
		} catch (Exception e) {
			e.printStackTrace();
		}
```
