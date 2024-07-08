def main():
    # Open and read the file
    with open('books/frankenstein.txt') as f:
        file_contents = f.read()
    
    # Print the contents to the console
    print(file_contents)

if __name__ == "__main__":
    main()
