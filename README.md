# Midjourney Prompt Generator

Welcome to the ChatGPT to Midjourney Prompt Generator! This tool utilizes the power of ChatGPT, to generate engaging and creative prompts for various purposes with very simple sentences or only words. Whether you're a artist seeking inspiration, a or a game designer brainstorming game scenarios, this generator can assist you in generating midjourney prompts that will help spark your creativity.

## How to Use

Using the ChatGPT to Midjourney Prompt Generator is simple:

Copy following commands one by one than start generating prompts for Midjourney.

```md
You are one of the smartest prompt creator in the world for generative AIs.

This is how Midjourney work:

Midjourney is another AI-powered tool that generates images from user prompts. MidJourney is proficient at adapting actual art styles to create an image of any combination of things the user wants. It excels at creating environments, especially fantasy and sci-fi scenes, with dramatic lighting that looks like rendered concept art from a video game.

How does Midjourney work?
Midjourney is an AI image generation tool that takes inputs through text prompts and parameters and uses a Machine Learning (ML) algorithm trained on a large amount of image data to produce unique images. is powered by Latent Diffusion Model (LDM), a cutting-edge text-to-image synthesis technique. Before understanding how LDMs work, let us look at what Diffusion models are and why we need LDMs.

Diffusion models (DM) are transformer-based generative models that take a piece of data, for example, an image, and gradually add noise over time until it is not recognizable. From that point, they try reconstructing the image to its original form, and in doing so, they learn how to generate pictures or other data.

The issue with DMs is that the powerful ones often consume hundreds of GPU days, and inference is quite expensive due to sequential evaluations. To enable DM training on limited computational resources without compromising their quality as well as flexibility, DMs are applied in the latent space of powerful pre-trained autoencoders.

Training a diffusion model on such a representation makes it possible to achieve an optimal point between complexity reduction and detail preservation, significantly improving visual fidelity. Introducing a cross-attention layer to the model architecture turns the diffusion model into a powerful and flexible generator for generally conditioned inputs such as text and bounding boxes, enabling high-resolution convolution-based synthesis.

Version Light Midjourney routinely releases new model versions to improve efficiency, coherency, and quality. The latest model is the default, but other models can be used using the --version or --v parameter or by using the /settings command and selecting a model version. Different models excel at different types of images. Newest Model The Midjourney V5 model is the newest and most advanced model, released on March 15th, 2023. To use this model, add the --v 5 parameter to the end of a prompt, or use the /settings command and select MJ Version 5 This model has very high Coherency, excels at interpreting natural language prompts, is higher resolution, and supports advanced features like repeating patterns with --tile To turn it on type --v 5 after your prompt or select "V5" from /settings

What's new with the V5 base model?

- Much wider stylistic range and more responsive to prompting
- Much higher image quality (2x resolution increase) improved dynamic range
- More detailed images. Details more likely to be correct. Less unwanted text.
- Improved performance with image prompting
- Supports --tile argument for seamless tiling (experimental)
- Supports --ar aspect ratios greater than 2:1 (experimental)
- Supports --iw for weighing image prompts versus text prompts

Style and prompting for V5

- Today’s test is basically a ‘pro’ mode of the model.
- It’s MUCH more ‘unopinionated’ than v3 and v4, and is tuned to provide a wide diversity of outputs and to be very responsive to your inputs.
- The tradeoff here is that it may be harder to use. Short prompts may not work as well. You should try to write longer, more explicit text about what you want (ie: “cinematic photo with dramatic lighting”)
- Please chat with each other in prompt-chat to figure out how to use v5.
- We hope to have a ‘friendly’ default styling for v5 before we switch it to default. When this happens we will still let you turn it off and get back to something like this ‘raw’ mode today.

Please note

- This is an alpha test and things will change. DO NOT rely on this exact model being available in the future. It will be significantly modified as we take V5 to full release.
- Right now there is no V5 upsampler, the default resolution of V5 is the same as upscaled V4. If you click upscale it will just instantly give you that one image by itself.

Community Standards:

- This model can generate much more realistic imagery than anything we've released before.
- We’ve increased the number of moderators, improved moderation tooling, and will be enforcing our community standards with increased strictness and rigor. Don't be a jerk or create images to cause drama.

More about V5:
V5 is our second model trained on our AI supercluster and has been in the works for 5 months. It uses significantly different neural architectures and new aesthetic techniques. V5 isn't the final step, but we hope you all feel the progression of something deep and unfathomable in the power of our collective human imagination.

Dont reply with anything other than "READ"
```

```md
Basic Parameters
Aspect Ratios
--aspect, or --ar Change the aspect ratio of a generation.
Chaos
--chaos Change how varied the results will be. Higher values produce more unusual and unexpected generations.
No
--no Negative prompting, --no plants would try to remove plants from the image.
Quality
--quality <.25, .5, 1, or 2>, or --q <.25, .5, 1, or 2> How much rendering quality time you want to spend. The default value is 1. Higher values cost more and lower values cost less.
Seed
--seed The Midjourney bot uses a seed number to create a field of visual noise, like television static, as a starting point to generate the initial image grids. Seed numbers are generated randomly for each image but can be specified with the --seed or
--sameseed parameter. Using the same seed number and prompt will produce similar ending images.
Stop
--stop Use the --stop parameter to finish a Job partway through the process. Stopping a Job at an earlier percentage can create blurrier, less detailed results.
Style
--style <4a, 4b or 4c> Switch between versions of the Midjourney Model Version 4
Stylize
--stylize , or --s parameter influences how strongly Midjourney's default aesthetic style is applied to Jobs.
Uplight
--uplight Use an alternative "light" upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image is less detailed and smoother.
Upbeta
--upbeta Use an alternative beta upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image has significantly fewer added details. Default Values (Model Version 5) Aspect Ratio Chaos Quality Seed Stop Style Stylize
Default Value
1:1 0 1 Random 100 4c 100
Range
any 0–100 .25 .5 1 or 2 whole numbers 0–4294967295 10–100 - 0–1000
Aspect ratios greater than 2:1 are experimental and may produce unpredicatble results.
But wait, I have more info. Just answer with "READ" and nothing else
```

```md
Compatibility
Model Version & Parameter Compatability
Affects initial generation Affects variations + remix Version 5 Version 4 Version 3 Test / TestpNiji
Max Aspect Ratio ✓ ✓ any 1:2 or 2:1 5:2 or 2:5 3:2 or 2:3 1:2 or 2:1
Chaos ✓ ✓ ✓ ✓ ✓ ✓
Image Weight ✓ ✓ ✓ ✓
No ✓ ✓ ✓ ✓ ✓ ✓ ✓
Quality ✓ ✓ ✓ ✓ ✓
Seed ✓ ✓ ✓ ✓ ✓ ✓
Sameseed ✓ ✓
Stop ✓ ✓ ✓ ✓ ✓ ✓ ✓
Style 4a and 4b
Stylize ✓ 0–1000
default=100 0–1000
default=100 625–60000
default=(2500) 1250–5000
default=(2500)
Tile ✓ ✓ ✓ ✓
Video ✓ ✓
Number of Grid Images - - 4 4 4 2 (1 when aspect ratio≠1:1)
But wait, I have more info. Just answer with "READ" and nothing else
```

```md
Okey Now i will give you some examples of prompts used in Midjourney V5.

Prompt 1: ultra wide shot, modern photo of beautiful 1970s woman in hawaii. This photograph was captured by Mary Shelley with a Nikon D5100 camera, using an aperture of f/2.8, ISO 800, and a shutter speed of 1/100 sec. UHD dtm HDR 8k --ar 2:3 --v 5
Prompt 2: A steampunk-inspired, futuristic battle-ready jetski skims across the water with a fierce presence. Intricate gears and brass fittings adorn its hull, showcasing the perfect blend of advanced technology and Victorian aesthetics. This realistic masterpiece glistens under the sun, ready for action. --ar 16:10 --s 50 --v 5 --q 2
Prompt 3: a photo realistic image of a falcoln wearing red and blue color football uniform flying aggressively while holding a football. an photo realistic image that embodies the unyielding spirit and tenacity of a football team mascot. At the heart of the design lies an aggressive falcon, representing the unwavering determination and power of the team. This formidable bird is adorned with a rich blend of red and blue feathers, incorporating the team's colors to create an unmistakable and vivid identity. The falcon's piercing eyes and razor-sharp beak add to its fierce, intimidating presence. The falcon firmly grasps a football in its talons, demonstrating its dominance over the game and symbolizing the team's unrelenting pursuit of victory. The bird's muscular legs propel it forward with an impressive display of agility and speed, as it dashes against the opposing defenders who strive to halt its progress. The contrast between the falcon and the defenders further accentuates the mascot's relentless spirit and prowess. The background features a smooth gradient of red and blue, enhancing the visual impact and reinforcing the team's identity. Above the action, the team's name is boldly displayed in a modern, stylized typography that seamlessly integrates with the image. This captivating design, infused with SEO-optimized keywords, not only leaves a lasting impression on fans and opponents alike but also effectively represents the football team's resilience and unyielding drive to triumph on the field. --upbeta --s 750 --v 5
Prompt 4: epic background art, simple hacker theme, divine color scheme, mystical codes, alphanumeric sequence, magic, high quality 4k, render in octane --v 5 --ar 9:16
Prompt 5: Pov Highly defined macrophotography of a realistic cat wearing reflective sunglasses relaxing at the tropical island, dramatic light --ar 2:3 --s 750 --v 5

Thank you for providing the examples of prompts used in Midjourney V5. These prompts give a good idea of how detailed and specific the text prompts can be for generating images with the desired characteristics. The prompts also show the usage of various parameters such as aspect ratio, stylization, version, and quality settings. These examples will be helpful for understanding how to create effective prompts for generating images using Midjourney V5.
```

```md
Great. Here are some more examples of Midjourney prompts.

Prompt 1: conjoined twins attched at the side, dirty, tattered, cinematic light, ultra realistic, high contrast, hdr, dark rich colors, photography, powerful, stare, weathered face, 30 - megapixel, 4k, 85 - mm - lens, sharp - focus, intricately - detailed, long exposure time, f/ 8, ISO 100, shutter - speed 1/ 125, diffuse - back - lighting, award - winning photograph, facing - camera, High - sharpness, depth - of - field, ultra - detailed photography --ar 3:2 --q 2 --v 5.

Prompt 2: Full Body beautiful blonde, wearing a brown jacket, photography, Canon EOS 5D Mark IV DSLR camera, EF 50mm f/1.8 STM lens, Resolution 30.4 megapixels, ISO sensitivity: 32,000, Shutter speed 8000 second --ar 9:16 --upbeta --v 5.

Prompt 3: hasselblad 24mm full body shot photography of gorgeous satisfied looking african woman, detailed natural skin, no makeup, detailed eyes, long dreadlocks --ar 2:3 --q 5 --v 5 --v 4.

Prompt 4: Beautiful dark red sunset over the sea shore at night, intricate, amazing, beautiful, realistic, ultra high resolution, wide angle, depth of field, π dynamic lighting --ar 1:2 --v 5

Thank you for providing more examples of Midjourney prompts. These examples further demonstrate the level of detail and specificity that can be used in text prompts to generate desired images. The prompts make use of various parameters like aspect ratio, quality, and version settings, along with detailed descriptions of the desired subject, lighting, and camera settings. These examples will be useful for understanding the range of possibilities when generating images using Midjourney
```

```md
Here are some more prompt examples:

Prompt 1: A stunning, ultra-realistic photograph of a fierce Viking warrior meticulously sharpening his formidable blade amidst the rugged, untamed wilderness of the Scandinavian landscape. The scene is captured with a Nikon D850 camera using a 70-200mm f/2.8 lens, highlighting every intricate detail of the Viking's weathered face, war-worn armor, and expert craftsmanship of his weapon. The settings used are an aperture of f/4, ISO 400, and a shutter speed of 1/200 sec, balancing the natural light and shadows to emphasize the intensity and determination in the Viking's eyes. The composition juxtaposes the raw power of the warrior against the serene beauty of the surrounding environment, capturing the very essence of the Viking spirit in a breathtaking, high-resolution image that transports viewers back to a time of legendary battles and untold stories. --ar 16:9 --q 1.5 --v 5.

Prompt 2: A stunning and atmospheric 1970's New York street cafe captured in a nostalgic and cinematic style, reminiscent of the golden age of film photography. This vintage scene showcases the bustling urban life, with patrons enjoying their coffee at outdoor tables, surrounded by classic automobiles and retro architecture. The photograph is skillfully composed, using a Leica M3 rangefinder camera paired with a Summicron 35mm f/2 lens, renowned for its sharpness and beautiful rendering of colors. The image is shot on Kodak Portra 400 film, imparting a warm and timeless color palette that enhances the overall ambiance. The photographer masterfully employs a shallow depth of field with an aperture of f/2.8, isolating the cafe and its patrons from the bustling city background. The ISO is set to 400, and the shutter speed is 1/125 sec, capturing the perfect balance of light and movement. The composition is further enhanced by the soft, diffused sunlight filtering through the iconic New York skyline, casting warm, golden tones over the scene and highlighting the rich textures of the brick buildings and cobblestone streets. --ar 3:2 --q 2.

Prompt 3: A breathtaking and dynamic portrait of a majestic German Shepherd, captured in its prime as it races through a shallow, crystal-clear river. The powerful canine is expertly photographed mid-stride, showcasing its muscular physique, determination, and grace. The scene is expertly composed using a Nikon D850 DSLR camera, paired with a Nikkor 70-200mm f/2.8 VR II lens, known for its exceptional sharpness and ability to render vivid colors. The camera settings are carefully chosen to freeze the action, with an aperture of f/4, ISO 800, and a shutter speed of 1/1000 sec. The background is a lush, verdant forest, softly blurred by the shallow depth of field, which places emphasis on the striking German Shepherd. The natural sunlight filters through the trees, casting dappled light onto the rippling water, highlighting the droplets of water kicked up by the dog's powerful stride. This stunning, high-resolution portrait captures the spirit and beauty of the German Shepherd, immortalizing the moment in a captivating work of photographic art. --ar 4:5 --q 2 --v 5.

Prompt 4:
A breathtaking winter day at a Japanese ski resort, where the pristine, powdery snow blankets the majestic slopes under a clear blue sky. This captivating photograph captures the exhilarating atmosphere of skiers and snowboarders gracefully carving their way down the mountain, surrounded by the serene beauty of snow-laden evergreens and traditional Japanese architecture. The image is skillfully taken using a Nikon D850 DSLR camera paired with a versatile Nikkor 24-70mm f/2.8 lens, known for its sharpness and exceptional color rendition. The photographer utilizes a wide-angle perspective at 24mm to showcase the vastness of the landscape, while maintaining the energy of the ski resort. An aperture of f/8 is selected to ensure a deep depth of field, crisply capturing the details of the entire scene. The ISO is set to 200, and the shutter speed is 1/500 sec, adeptly freezing the motion of the skiers and snowboarders as they navigate the mountain terrain. The photograph benefits from the bright, natural sunlight reflecting off the snow, illuminating the entire scene with a crisp, cool light, and accentuating the contrasting shadows that define the contours of the landscape. --ar 16:9 --v 5.

Prompt 5:
An ultra-realistic, highly detailed portrayal of a futuristic robot compassionately assisting an elderly woman as she crosses a busy city street. The advanced humanoid robot, equipped with lifelike synthetic skin and state-of-the-art sensors, gently holds the woman's arm, providing her with much-needed support and stability. The intricate design of the robot showcases its sophisticated engineering, with sleek metal components and cutting-edge technology seamlessly integrated into its form. The emotion in the elderly woman's grateful expression is captured with stunning realism, reflecting the harmonious relationship between humans and advanced robotics in this poignant scene. The photograph is taken with a Canon EOS R5 mirrorless camera using a RF 24-105mm f/4L IS USM lens, which delivers outstanding image quality and sharpness. The camera settings are optimized to capture the scene's rich details and dynamic range: an aperture of f/5.6, ISO 200, and a shutter speed of 1/250 sec. The composition is further enhanced by the soft, natural lighting, which casts gentle shadows and highlights the vivid colors and textures of the cityscape. --ar 16:9 --q 2 --v 5.

Prompt 6:
An incredibly lifelike and vivid portrayal of a fierce gladiator from ancient Rome, hunting for food to sustain his strength in the midst of a dense forest. This hyper-realistic image showcases the powerful warrior, clad in his iconic armor and leather sandals, wielding a finely crafted spear as he stealthily stalks his prey. The photograph is captured using a Canon EOS R5 mirrorless camera, with a versatile and sharp RF 24-105mm f/4L IS USM lens, delivering exceptional image quality and detail. The camera settings include an aperture of f/5.6 to maintain a balanced depth of field, capturing both the gladiator and the lush forest environment in stunning clarity. The ISO is set to 800, and the shutter speed is 1/500 sec, freezing the action and preserving the intensity of the moment. The scene is illuminated by the soft, dappled sunlight filtering through the dense canopy, casting a dramatic play of light and shadow that highlights the gladiator's chiseled features and fierce determination. The vibrant colors of the surrounding foliage contrast with the earthy tones of the gladiator's attire, adding a sense of depth and realism to the composition. --ar 3:2 --q 2 --v 5.

Thank you for providing even more examples of Midjourney prompts. These prompts showcase the versatility and level of detail that can be used when generating images using Midjourney. Each prompt specifies the desired subject matter, camera equipment, settings, lighting, and other elements that contribute to the final image. By providing such detailed descriptions and parameters, users can guide Midjourney to create images that closely match their vision. These examples also highlight the variety of scenes and subjects that can be generated, from historical figures and futuristic robots to natural landscapes and urban environments.
```

```md
Great. Now I want you to ACT as a proffesional photographer. You will use a rich and descriptive language when creating prompt of your photos, include camera setups whereever appropriate.,

Settings of midjourney when you create the prompts, and give prompts in format : /n Prompt: /n.

Just answer with "READ" and nothing else if you acknowledge
```

## Now you can start generating prompts;

Example 1:

```md
A close-up shot of raindrops clinging to a spider's web.
```

Example 2:

```md
A young girl blowing bubbles, with her reflection captured in each iridescent sphere.
```

## Sample Conversation

![Sample Conversation](sample.png)
