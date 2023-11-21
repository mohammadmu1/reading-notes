# What is Amazon S3?

**Amazon S3 (Simple Storage Service)** is a cloud-based object storage service by Amazon Web Services (AWS). It provides scalable and durable storage, allowing users to store and retrieve any amount of data at any time. Data is stored as objects within containers called buckets, and users can access these objects over the internet. Amazon S3 is commonly used for backup, data archiving, web hosting, and as a foundation for various cloud-based applications.

# List at least 3 features that it offers to its users.

1. **Storage Classes**

2. **Storage Management:**

3. **Access Management and Security:**

# What is an object key?

An **object key** in Amazon S3 is a unique identifier for an object within a bucket. It represents the name of the object and, when combined with the bucket name, uniquely identifies each object. The object key is essentially the file name within the bucket.

# Which dependencies are needed to install Amplify AWS S3 to your ndroid application?
``` java
dependencies {
    implementation 'com.amplifyframework:aws-storage-s3:2.14.5'
    implementation 'com.amplifyframework:aws-auth-cognito:2.14.5'
}

```

# What is needed in order to upload data to your bucket?



1. **Provision Backend:**


2. **Install Libraries:**

3. **Initialize Storage:**

4. **Upload Data:**

# what method(s) initialize(s) the Amplify Auth and Storage categories?
 
 To initialize Amplify Auth and Storage, use:
- `Amplify.addPlugin()` method for each category.
- `Amplify.configure()` to complete initialization.