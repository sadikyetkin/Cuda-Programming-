# Cuda-Programming-
Learning the Cuda Parallel Programming 

This is the begining of CUDA Parallel Programming Tutorial for myself. 


#define TILE_W  16
#define TILE_H  16
#define R       2         // filter radius
#define D       (R*2+1)   // filter diameter
#define S       (D*D)
#define BLOCK_W (TILE_W+(2*R))
#define BLOCK_H (TILE_H+(2*R))
  
