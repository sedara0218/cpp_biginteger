# cpp_biginteger
A BigInteger class for c++

## How to use:
#### 1. Download the files to a local directory
#### 2. At the top of the main cpp file in which you are utilizing bigint; type: `#inlcude "bigint.h"`
#### 3. Use it with the methods listed in the headers.

## Methods to use:
```
		bigint();
    
		template <class T>
		bigint(T n);

		std::string to_string();
		int size() const;
		std::vector<int>::iterator begin();
		std::vector<int>::iterator end();
		std::vector<int>::reverse_iterator rbegin();
		std::vector<int>::reverse_iterator rend();
		std::vector<int>::const_reverse_iterator crbegin() const;
		std::vector<int>::const_reverse_iterator crend() const;
		std::vector<int> getNum();
		bool getSign() const;
		void setSign(bool);
		void setNum(std::vector<int>);

		bool is_even();
		int get_last_digit();
		bigint abs();
		bigint negate(); //-1 * *this

		template <class T>
		void operator = (T i);
    
		template <class T>
		bool operator == (T i);
    
		template <class T>
		bool operator != (T i);
    
		template <class T>
		bool operator < (T i);
    
		template <class T>
		bool operator > (T i);
    
		template <class T>
		bool operator <= (T i);
    
		template <class T>
		bool operator >= (T i);
    
		template <class T>
		bigint operator + (T i);
    
		template <class T>
		bigint operator - (T i);
    
		template <class T>
		void operator += (T i);
    
		template <class T>
		void operator -= (T i);
    
		template <class T>
		bigint operator * (T i);

		void operator ++ ();
		void operator -- ();
```
## Extensions:
Will be adding functionality to the following functions:
```
		//EXTENSION FUNCTIONS TO ADD
		bigint operator / (bigint &b);
		bigint operator % (bigint &b);
		bigint pow(int exponent);
		int hashCode();
		double to_double();
		float to_float();
		long long to_longlong();
		long to_long();
		int to_int();
```
