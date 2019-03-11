# Tensorflow projector


## URL query format
 * config: an URL to the config file
 * tensorName: name of the tensor
 * tensorShape: the shape of the tensor separated by `,`, e.g: `1000,128`
 * tensorPath: an URL to the tensor file (raw bytes)
 * metadataPath: an URL to the metadata file path (tsv format)
 * spriteImagePath: an URL to the sprite image file (png format).
 * spriteSingleImageDim: the shape of a single sprite image separated by `,`, e.g.: `28,28`
 * select: select an embedding by index defined in the config file
 * bookmark: load the bookmark by index defined in the config file
 * type: choose the projection types: `pca`, `tsne` or `custom`.

 
