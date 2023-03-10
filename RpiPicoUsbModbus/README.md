# verify PICO_SDK_PATH is not set

This may take some time..

export "PICO_SDK_PATH"="" -> not set SDK path

echo "$PICO_SDK_PATH" -> check it's not set

# build and run project

mkdir build

cd build

cmake ..

make

cp file_name.uf2 /media/user_name/RPI-RP2/

# .gitignore file created to not commit the build and lib files


# Notes

GPIO's 4 and 5 not used due to conflit probability with the uart line