1. how to sort a vector in descending order -> sort(v.rbegin(),v.rend())
2. converting a map into a vector of pair -> vector<pair<char,int>> vec(m.begin(),m.end())

3. using lambda function to sort a vector<<pair<char,int>> on the basis of the 2nd element at each index
4. sort(v.begin(),v.end(),[](auto& a, auto& b){
                         return a.second>b.second
                          });                                 // here we can't use v.rbegin() and v.rend()

5. 
