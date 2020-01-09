# Compile
g++ range-to-tcam.cpp -o range_to_masks -lgmp

# Run example

./range_to_masks --bit-width 16 --min 1 --max 65534

Code supports bit-width of any size including 64 or 128 bits