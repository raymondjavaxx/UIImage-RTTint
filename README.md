# UIImage+RTTint

Retina-aware category for tinting, darkening and lightening a UIImage.

## Usage

	#import "UIImage+RTTint.h"
	...
	UIImage *image = [UIImage imageNamed:@"Logo.png"];
	UIImage *tinted = [image rt_tintedImageWithColor:[UIColor redColor] level:0.5f];

See [UIImage+RTTint.h](UIImage+RTTint.h) for more.

## Copyright

Copyright © 2013 Ramon Torres. Released under the MIT License.
