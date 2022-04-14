# verdaccio-test
This is to see if verdaccio can pull dependencies recursively

## Dependencies
@zyc/package-b depends on @zyc/package-a depends on chalk

## Usage
1. Install verdaccio
2. Publish @zyc/package-a into verdaccio
3. Install dependencies in @zyc/package-b
4. Verify chalk is installed in @zyc/package-b
