# gfg
#Find the element that appears once
```
int search(int A[], int N){
	    //code
	    for(int i=0;i<N;i++)
	    {
	        auto l=lower_bound(A,A+N,A[i]);
	        auto u=upper_bound(A,A+N,A[i]);
	        if(u-l==1)
	            return A[i];
	    }
	    //return 0;
	}
```
