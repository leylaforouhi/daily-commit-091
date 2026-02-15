def find_second_largest(numberS):
    unique_numbers = list(set(numbers))
    unique_numbers.sort()
    if len(unique_numbers) < 2:
        return None
    return unique_numbers[-2]

if __name__ == "__main__":
    nums = [10, 20, 4, 45, 99, 99]
    print(f"Numbers: {nums}")
    print(f"Second largest: {find_second_largest(nums)}")
