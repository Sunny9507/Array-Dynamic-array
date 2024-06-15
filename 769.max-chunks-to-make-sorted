class Solution {
public:
    int maxChunksToSorted(vector<int>& arr) {
        int n = arr.size();
        int max_val = -1, chunks = 0;

        for (int i = 0; i < n; ++i) {
            max_val = max(max_val, arr[i]);  
            if (max_val == i) {  
                chunks++;
            }
        }
        return chunks;
    }
};
