# Report-01
first lab timp
'''
$ wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz
'''
![first sqreen](https://user-images.githubusercontent.com/112761204/222981280-828ef8a1-7b10-4666-a69a-b7c23c6b8c46.png)

'''
$ tar -xvf boost_1_69_0.tar.gz
'''
![sqreen 2](https://user-images.githubusercontent.com/112761204/222981572-b30593b7-1a85-4d5d-bb3e-fa23de8c35b2.png)

'''
$ ls -l | grep "^-" | wc -l
'''
![sqreen 3](https://user-images.githubusercontent.com/112761204/222981589-90a0402b-99fa-46bf-a1d7-a5fd5119e4ce.png)

'''
$ ls -l -R | wc -l
'''
![s 4](https://user-images.githubusercontent.com/112761204/222981609-efbde7b4-42d2-49b9-8349-b30d62912430.png)

'''
$ ls -l -R | grep -c *.hpp
$ ls -l -R | grep -c *.cpp
$ ls -l -R | grep -v *.hpp | grep -v *.cpp | grep -v 'итого' | wc -l
'''
![s 5](https://user-images.githubusercontent.com/112761204/222981627-b7d0e8a7-5273-4765-9f51-521ba24d1404.png)

'''
$ find $PWD -type f -name any.hpp
'''!
[s 6](https://user-images.githubusercontent.com/112761204/222981640-08975684-f402-47c3-9b54-2e34720a4ada.png)

'''
$ grep -R -l "boost::asio"
'''!
[7](https://user-images.githubusercontent.com/112761204/222981657-7c49c610-6620-45c0-af29-ffdd92fa46b6.png)

'''
$ ./bootstrap.sh —prefix=boost_output
$ ./b2 install
'''!
[8](https://user-images.githubusercontent.com/112761204/222981667-aa577a03-05cf-4bad-ad9a-b6e7318b7c19.png)

'''
$ mv ~/boost_1_69_0/boost_output/lib ~/boost-libs
'''
![9](https://user-images.githubusercontent.com/112761204/222981675-968f5362-ae66-402b-81d5-1828bfd61704.png)

'''
$ du -h -a | sort -h
'''
![10](https://user-images.githubusercontent.com/112761204/222981690-27d722a9-6373-4274-90f3-bdf12a141b33.png)

'''
$ du -h -a | sort -r -h | head -n 10
'''!
[11](https://user-images.githubusercontent.com/112761204/222981699-2ba2e0b2-848c-42a8-b85c-c844e0f1db6c.png)
